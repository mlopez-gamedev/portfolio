<template>
  <div>
    <h1>Resume</h1>

    <div class="photo">
      <img src="img/resume-photo.jpg" alt="Photo of Miguel López" />
    </div>
    <div class="paragraph">
      <div>
        I'm <strong>Miguel López</strong>, a video game developer specialized in Unity programming with extensive experience as a free-to-play game designer.
      </div>
      <div style="margin-top: 20px;">
        After 7 years creating idle games for mobile devices, I sold my company, <a href="https://www.koronstudios.com" target="_blank">Koron Studios</a>, to bring my expertise to other types of projects and continue growing professionally.
      </div>
      <div style="margin-top: 20px;">
        I am currently working at <a href="https://www.odderslab.com" target="_blank">Odders Lab</a>, developing Virtual Reality and Mixed Reality video games for the renowned fitness brand <strong>Les Mills</strong>.
      </div>
      <h3>Key achievements</h3>
      <div style="margin-top: 20px;">
        <ul>
          <li><strong>15+ years</strong> of experience programming in C# (starting with .NET Framework, now focused on Unity).</li>
          <li><strong>10+ years</strong> of experience in video game development, taking on roles such as Unity programmer, game designer, UX, monetization, live ops, scrum master, and product manager.</li>
          <li><strong>7 commercial games</strong> published for mobile devices.</li>
          <li><strong>1 commercial game</strong> published for PlayStation 4.</li>
          <li><strong>1 XR game</strong> published for Meta Quest, PlayStation 5 and Pico XR (involved in late stages of development)</li>
          <li>Over <strong>50 games</strong> developed in total (professional, side projects, and game jams).</li>
          <li><strong>1 company</strong> founded and successfully sold after 7 years of operation: <a href="https://www.koronstudios.com" target="_blank">Koron Studios</a></li>
        </ul>
      </div>
      <div style="margin-top: 20px;">If you think my profile aligns with your company's needs, feel free to <router-link to="/contact">reach out</router-link>.</div>
      <div style="margin-top:20px; margin-bottom:20px;">
        <a class="download-link" href="d/miguel-lopez-resume-en.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Download as PDF 🇬🇧</a>
        <a class="download-link" href="d/miguel-lopez-resume-es.pdf" target="_blank"><i class="fa fa-download fa-lg fa-fw"></i> Descargar en PDF 🇪🇸</a>
        <div style="clear:both"></div>
      </div>
    </div>

    <div style="clear:both"></div>

    <div class="full-content">
      <h2>Work Experience</h2>

      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/odders-lab-logo.jpg" alt="Odders Lab Logo" />
        </div>
        <div class="timeline-details">
          <h3>Odders Lab</h3>
          <h4>Fullstack Game Programmer <strong class="date">January 2024 - Present</strong></h4>
          <div>
            <ul>
              <li>Development and documentation of VR game features in Unity.</li>
              <li>Bug fixing and fine-tuning gameplay mechanics.</li>
              <li>Implemented analytics events for measuring KPIs.</li>
              <li>Collaborated with the backend team on REST API features using Node.js.</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/koron-studios-logo.jpg" alt="Koron Studios Logo" />
        </div>
        <div class="timeline-details">
          <h3>Koron Studios</h3>
          <h4>CEO & Game Designer <strong class="date">March 2021 - January 2023</strong></h4>
          <div>
            <ul>
              <li>Directed company strategy and business development.</li>
              <li>Analyzed and documented game systems and balanced game economies.</li>
              <li>Managed live operations and adapted products to user needs based on market analysis.</li>
            </ul>
          </div>
          <h4>Co-founder & Game Programmer <strong class="date">June 2019 - March 2021</strong></h4>
          <div>
            <ul>
              <li>Updated the Kraken Framework for Free2Play game development.</li>
              <li>Developed mobile games using Unity 3D.</li>
              <li>Monitored and resolved technological needs for the company.</li>
            </ul>
          </div>
          <h4>Scrum Master & Game Programmer <strong class="date">February 2017 - June 2019</strong></h4>
          <div>
            <ul>
              <li>Managed projects using LEAN and Scrum methodologies.</li>
              <li>Designed architecture for video games and programmed mobile games in Unity 3D.</li>
              <li>Developed project templates and tools to streamline development.</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/pancake-team-logo.jpg" alt="Pancake Team Logo" />
        </div>
        <div class="timeline-details">
          <h3>Pancake Team</h3>
          <h4>Studio Head & Game Programmer <strong class="date">May 2016 - February 2017</strong></h4>
          <div>
            <ul>
              <li>Directed studio business strategy and developed mobile games for Android and iOS.</li>
              <li>Collaborated on game design, UX, and project management.</li>
              <li>Released "The Abyss: Solve the Board" on Google Play and iTunes.</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/koth-studio-logo.jpg" alt="KOTH Studios Logo" />
        </div>
        <div class="timeline-details">
          <h3>KOTH Studios</h3>
          <h4>Game Designer & Product Manager <strong class="date">March 2015 - December 2015</strong></h4>
          <div>
            <ul>
              <li>Designed iOS and PS4 games.</li>
              <li>Developed production and quality plans.</li>
              <li>Managed and monitored the development process.</li>
              <li>Provided technical support and programming in Unity 3D and PHP.</li>
            </ul>
          </div>
        </div>
      </div>

      <!-- <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/bitoon-games-logo.jpg" alt="Logo de Bitoon Games" />
        </div>
        <div class="timeline-details">
          <h3>Bitoon Games</h3>
          <h4>Programmer <strong class="date">September 2012 - March 2014</strong></h4>
          <div>
            <ul>
              <li>Developed backend web services using PHP and MySQL.</li>
              <li>Designed and maintained databases with PostgreSQL.</li>
              <li>Provided frontend support with JavaScript, HTML5, and CSS.</li>
              <li>Supported the Usability department with wireframe designs.</li>
            </ul>
          </div>
        </div>
      </div> -->

      <h2>Skills</h2>

      <div class="skill-set">
        <h3>Programming</h3>
        <div class="skill">Coding Principles</div>
        <div class="skill">Clean Code</div>
        <div class="skill">Programming Patterns</div>
        <div class="skill">MVC</div>
        <div class="skill">MVP</div>
        <div class="skill">Hexagonal architecture</div>
        <div style="clear:both" />
      </div>
      
      <div class="skill-set">
        <h3>Coding Languages</h3>
        <div class="skill">C#</div>
        <div class="skill">C++</div>
        <div class="skill">MySQL</div>
        <div class="skill">PHP</div>
        <div class="skill">Java Script</div>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div style="clear:both" />
      </div>

      <div class="skill-set">
        <h3>Game Engines</h3>
        <div class="skill">Unity</div>
        <div class="skill">Godot</div>
        <div class="skill">Unreal</div>
        <div class="skill">Eager to learn a new one!</div>
      </div>
      <div style="clear:both" />

      <div class="skill-set">
        <h3>GameDev</h3>
        <div class="skill">Scrum</div>
        <div class="skill">Game Design</div>
        <div class="skill">UX / Game feeling</div>
        <div class="skill">Live Ops</div>
        <div class="skill">F2P Monetization</div>
        <div class="skill">Narrative</div>
      </div>
      
      <div class="skill-set">
        <h3>Soft skills</h3>
        <div class="skill">Communication</div>
        <div class="skill">Organization</div>
        <div class="skill">Collaboration</div>        
        <div class="skill">Adaptability</div>
        <div class="skill">Innovation</div>
        <div class="skill">Problem-solving</div>
        <div class="skill">Attention to detail</div>
        <div class="skill">Manners</div>
      </div>
      
      <div class="skill-set">
        <h3>Languages</h3>
        <SkillRate name="Spanish" :rate="5" />
        <SkillRate name="English" :rate="3" />
      </div>
      <div style="clear:both" />

      <h2>Certifications</h2>
      <ul>
        <li>Video game development in Godot 4</li>
        <li>Creation of online multiplayer in Unreal engine</li>
        <li>Video game development in Unreal with C++</li>
        <li>Shader Graph expert with Unity 2021</li>
        <li>UX Design for video games</li>
        <li>Narrative design and script writing for video games</li>
        <li>Design Patterns for Game Programming</li>
        <li>SOLID and Clean Code for Videogames</li>
        <li>Microsoft Certified Technology Specialist (MCTS)</li>
        <li>MCTS: .Net Framework 2.0: Windows Applications</li>
        <li>MCTS: .Net Framework 2.0: Distributed Applications</li>
      </ul>

      <h2>Education</h2>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/cice-logo.jpg" alt="Logo de CICE" />
        </div>
        <div class="timeline-details">
          <h3>CICE</h3>
          <h4>Professional Course in Game Design and Producing <strong class="date">2012 - 2014</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/uem-logo.jpg" alt="Universidad Europea de Madrid Logo" />
        </div>
        <div class="timeline-details">
          <h3>Universidad Europea de Madrid</h3>
          <h4>Master's in Game Design and Programming <strong class="date">2010 - 2011</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/proaudio-logo.jpg" alt="ProAudio School Logo" />
        </div>
        <div class="timeline-details">
          <h3>ProAudio School</h3>
          <h4>Master's in Musical Production <strong class="date">2019 - 2020</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/escuela-de-escritores-logo.jpg" alt="Escuela de Escritores Logo" />
        </div>
        <div class="timeline-details">
          <h3>Escuela de Escritores</h3>
          <h4>Novel pathway I: Narrative techniques in the novel <strong class="date">2015 - 2016</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/adalid-inmark-logo.jpg" alt="Adalid Inmark Logo" />
        </div>
        <div class="timeline-details">
          <h3>Adalid Inmark</h3>
          <h4>Computer Analyst and Programmer Java Premium <strong class="date">2014 - 2015</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/fortec-logo.jpg" alt="FORTEC Logo" />
        </div>
        <div class="timeline-details">
          <h3>FORTEC</h3>
          <h4>Digital Marketing 2.0 <strong class="date">2013 - 2014</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <div class="timeline-section">
        <div class="timeline-logo">
          <img src="img/resume/alhambra-eidos-logo.jpg" alt="Alhambra-Eidos Logo" />
        </div>
        <div class="timeline-details">
          <h3>Alhambra Eidos</h3>
          <h4>Master's in .NET Software Development <strong class="date">2008 - 2009</strong></h4>
          <div style="clear:both"></div>
        </div>
      </div>
      <h2>Besides...</h2>
      <div>
        <h3>I ❤️ Game Jams</h3>
        <div>I join every game jam I can because it's where I get to create, experiment, and truly express my artistic side.</div>
        
        <h3>I 🧡 Indie games</h3>
        <div>I don't dedicate as much time to gaming as I used to, so I now prefer short, original, and impactful experiences: '<em>Papers, Please</em>', '<em>To the Moon</em>', '<em>Faster Than Light</em>', '<em>Into the Breach</em>'...</div>

        <h3>I 💛 Board Games</h3>
        <div>I love playing games, especially spending time with my friends. After 8 hours in front of a screen, I find I really need to step into the real world. Board games give me that connection and are a great opportunity to discover fresh, engaging mechanics.</div>
        
        <h3>I 💜 Science & useless knowledge</h3>
        <div>I could easily spend hours listening to podcasts on humor, history, psychology, or science—especially science when it’s math-free. I'm particularly passionate about physics, space, anthropology, geology, and nature in general</div>

        <h3>I 💚 Active lifestyle</h3>
        <div>I spend my whole workday sitting and stuck inside, so when the bell rings, it’s time to get out! I love playing padel, grabbing a drink at a terrace, hiking, visiting towns, going to the beach in summer, or just taking a slow walk around Seville feeding pigeons at Maria Luisa Park. Anything to move a bit!</div>

        <h3>I 🤎 Coffee</h3>
        <div>I’m a caffeine-powered coding machine. No coffee, no code.</div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import SkillRate from "@/components/SkillRate.vue";

export default Vue.extend({
  name: "Resume",
  components: {
    SkillRate,
  },
});
</script>

<style scoped>
h2 {
  font-weight: 100;
  font-size: 2em;
  margin: 0px;
  padding: 0px;
  padding-top: 50px;
}
h3 {
  font-weight: 100;
  font-size: 1.6em;
  margin: 0px;
  padding: 0px;
  padding-top: 30px;
}

h4 {
  font-weight: 100;
  font-size: 1.3em;
  margin: 0px;
  padding: 0px;
  padding-top: 15px;
  font-style: italic;
  align-items: center;
}

.timeline-details h4 {
  display: flex;
  justify-content: space-between;
}

.timeline-logo img {
  width: 100px;
  height: 100px;
  float: left;
  margin-top: 30px;
  margin-right: 15px;
  border-radius: 40%;
}

.timeline-section {
  display: flex;
}

.timeline-details {
  margin-left: 15px;
  flex: 1;
}

.date {
  font-weight: bold;
  text-align: right;
  font-size: 0.75em;
}

.paragraph {
  max-width: 700px;
}

.download-link {
  float:left;
  margin-right: 50px;
}

.full-content div {
  max-width: 1000px;
}

.skill-set {
  display: inline-block;
}

.skill-set h3 {
  padding-bottom: 10px;
}

.skill {
  float:left;
  border:1px solid hsla(0,0%,86.3%,.44);
  border-radius: 4px;
  padding:2px 10px;
  margin:5px
}

.photo img {
  height: 300px;
  width: 300px;
  border-radius: 40%;
}

.tech-stack {
  font-style: italic;
}

.photo {
  text-align: center;
}

@media only screen and (max-width: 1024px) {
  .timeline-logo {
    display: none;
  }

  .timeline-details {
    margin-left: 0;
  }

  .timeline-details h4 {
    justify-content: normal;
    display: block;
  }

  .date {
    display: block;
    text-align: left;
    margin-top: 5px;
  }
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }
  
  .photo {
    float: right;
    padding-left: 80px;
    padding-right: 120px;
  }

  .skill-set {
    float: left;
    padding-right: 60px;
    max-width: 300px !important;
  }
}
</style>
