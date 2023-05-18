<style>
  .grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    grid-gap: 20px;
    justify-items: center;
    align-items: center;
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  .light-pink-box {
    padding: 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
  }

  .light-pink-box img {
    max-width: 100%;
    height: auto;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }

  .work-item-inner {
    display: flex;
    align-items: center;
    text-align: left;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  .work-item-inner img {
    margin-right: 20px;
    width: 100%;
    max-width: 300px;
    height: auto;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }

 

  .red-box {
    border: none;
    padding: 20px;
    text-align: center;
  }

  .light-pink-button {
    background-color: pink;
    color: white;
    border: none;
    padding: 5px 10px;
    cursor: pointer;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }

  .my-ux-skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 30px;
  }

  .my-ux-skills .skill-card {
    width: 300px;
    padding: 20px;
    margin: 10px;
    text-align: center;
    border: 2px solid lightgray;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }

  .my-ux-skills .skill-card img {
    max-width: 100%;
    height: auto;
    box-shadow: none;
  }
  @media (max-width: 600px) {
    .flex-container {
      flex-direction: column;
    }
 
    .flex-item {
      width: 100%;
    }

    .grid-container {
      grid-template-areas:
        "header"
        "section"
        "footer";
      grid-template-rows: auto 1fr auto;
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="red-box">
  <h1>My UX Skills</h1>
  <section>
    <div class="my-ux-skills">
      <div class="skill-card">
        <img src="https://i1.wp.com/a16z.com/wp-content/uploads/2021/04/Market-for-User-Research-Platforms-Inline-Graphic-1.png?resize=1024%2C512&ssl=1" alt="Skill 1">
        <h1>User Research</h1>
        <p>Designing and creating intuitive and user-friendly digital experiences that meet the needs and expectations of users, focusing on enhancing usability, accessibility, and overall user satisfaction.</p>
      </div>
      <div class="skill-card">
        <img src="https://www.betabreakers.com/wp-content/uploads/2020/12/122780970_s.jpg" alt="Skill 2">
        <h1>User Interface Design</h1>
        <p>Designing visually appealing and interactive digital interfaces that facilitate effective user interactions, encompassing the arrangement of elements, visual aesthetics, and the seamless integration of design and functionality.</p>
      </div>
      <div class="skill-card">
        <img src="https://uploads-ssl.webflow.com/615af81f65d1ab72d2969269/62efdf9840dca733692cdd48_web%20dev%20basics.jpg" alt="Skill 3">
        <h1>Web Development</h1>
        <p>Designing, building, and maintaining websites and web applications, utilizing programming languages like HTML, CSS, and JavaScript to create functional and interactive online experiences.</p>
      </div>
    </div>
  </section>
</div>

<section>
  <div class="red-box">
    <h1>My Work</h1>
    <div class="grid-container">
      <div class="light-pink-box">
        <img src="https://images.unsplash.com/photo-1513159446162-54eb8bdaa79b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Image 1">
        <div class="work-item-details">
          <h4>Title 1</h4>
          <p>Description 1</p>
          <button class="light-pink-button">Button 1</button>
        </div>
      </div>
      <div class="light-pink-box">
        <img src="https://images.unsplash.com/photo-1503676260728-1c00da094a0b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Image 2">
        <div class="work-item-details">
          <h4>Title 2</h4>
          <p>Description 2</p>
          <button class="light-pink-button">Button 2</button>
        </div>
      </div>
      <div class="light-pink-box">
        <img src="https://images.unsplash.com/photo-1555774698-0b77e0d5fac6?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=600&q=80" alt="Image 3">
        <div class="work-item-details">
          <h4>Title 3</h4>
          <p>Description 3</p>
          <button class="light-pink-button">Button 3</button>
        </div>
      </div>
    </div>
    <h3>Additional Information</h3>
  </div>
</section>
