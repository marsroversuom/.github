# MANSED's MARS Rover Project!

## Our Goal

Our mission is to build innovative rovers to excel in competitions like the ERC and UKSEDs, creating a community where students can develop real-world engineering and teamwork skills.

## Our Progress

### The Prototype

This was an initial realisation of an idea to something that functions on purely on basic materials, stripped bare of any bells and whistles. This model was powered up by individual servos that can spin each wheel as well as high torque low speed drive motors controlled by an arduino. We were able to display the wireless capabilities in even an early model using the Raspberry Pi 4.

<div style="display: flex; justify-content: center; align-items: center; gap: 40px;">
  <img src="image.png" alt="description for first image" style="height: 300px; width: auto;">
  <img src="image-1.png" alt="description for second image" style="height: 300px; width: auto;">
</div>

### V1 - present

This is fully featured and polished model that we hope to present to raise funds for the final rover. This model is due to be 3D printed and finished by the end of 2025, and features:

- Rocker-bogie suspension
- Robotic arm capable of basic movement
- On-board camera capable of streaming to a laptop

The goal of this design is to have something that can be scaled into the final competiton version, with proper metal parts.

<div style="display: flex; justify-content: center; align-items: center; gap: 40px;">
  <img src="image-3.png" alt="description for image 3" style="height: 400px; width: auto;">
  <img src="image-4.png" alt="description for image 4" style="height: 400px; width: auto;">
</div>

## Meet the team

<div style="display: flex; justify-content: center; align-items: center; gap: 40px;">
  <img src="image-5.jpg" alt="description for image 3" style="height: 400px; width: auto;">
</div>

<style> 
  /* --- CORRECTED STYLES --- */

/* Main container for the cards */
.profile-container {
  display: flex;
  overflow-x: auto;
  gap: 10px;
  padding: 10px; 
  font-family: sans-serif;
  /* 👇 CHANGE: 'stretch' makes all cards match the height of the tallest one */
  align-items: stretch; 
}

/* Individual card styling */
.profile-card {
  flex-shrink: 0;
  width: 150px; 
  /* 👇 REMOVED: height: 100%; is no longer needed */
  background-color: #4f4a4aff;
  border: 1px solid #4f4a4aff;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  text-align: center;
  /* 👇 CHANGE: Switched to a dark color for readability */
  color: white; 
  padding: 15px;
  /* 👇 ADDED: Ensures content is vertically aligned nicely */
  display: flex;
  flex-direction: column;
}

/* --- The rest of your styles can stay the same --- */
h3 {
  margin-top: 0;
}
.title {
  color: white;
  font-size: 0.9em;
}
.description {
  font-size: 0.8em;
  flex-grow: 1; /* Allows this element to fill remaining space */
}

#hi {
  /* This makes the body a flex container */
  display: flex;
  
  /* This centers the content (your card container) horizontally */
  justify-content: center; 
  
  /* This centers the content vertically */
  align-items: center;
  
  margin: 0; 
}
</style>
<div id = "hi">
<div class="profile-container">

  <div class="profile-card">
    <h3>Albert</h3>
    <p class="title">AI/Computer science advisor</p>
    <p class="description">Expert in front-end frameworks and building scalable user interfaces.</p>
  </div>

  <div class="profile-card">
    <h3>Arai</h3>
    <p class="title">Project Lead</p>
    <p class="description">Dedicated to delivering high-quality projects on time and within budget.</p>
  </div>

  <div class="profile-card">
    <h3>Yang</h3>
    <p class="title">Onshape/CAD Lead</p>
    <p class="description">Passionate about creating intuitive and beautiful user experiences.</p>
  </div>

  <div class="profile-card">
    <h3>Keshav Kannan</h3>
    <p class="title">Software/Electrical Lead</p>
    <p class="description">Helps code software that manages the signals between the rover, computer and motors, ensuring that all the components communicate to each other effectively.</p>
  </div>

</div>
</div>
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
