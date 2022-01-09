<script>
  import CourseworkCard from "./CourseworkCard.svelte";
  import ExperienceCard from "./ExperienceCard.svelte";
  import CompetitionCard from "./CompetitionCard.svelte";
  import SkillsList from "./SkillsList.svelte";
</script>

<ul class="navbar">
  <li><a href="#intro">Intro</a></li>
  <li><a href="#education">Education</a></li>
  <li><a href="#experience">Experience</a></li>
  <li><a href="#competitions">Competitions</a></li>
  <li><a href="#skills">Skills</a></li>
</ul>
<section id="intro">
  <div class="intro-content">
    <h1 class="intro-text">
      Hello, I'm <span class="name">Marshall Shine</span>
    </h1>
    <img
      class="my-picture"
      src="./headshot.jpg"
      alt="Marshall Shine in professional attire"
    />
  </div>
  <p id="intro-synopsis">
    I am currently a Junior at Missouri State University where I study
    Accounting and IT Infrastructure. I also work at my university for the
    College of Business as an IT Support Specialist. Through my work experience
    and education, I plan on creating a career where I can combine both
    disciplines.
  </p>
</section>
<section id="education">
  <h2>Education</h2>
  <div class="subsection">
    <h3 class="subsection-title">Summary</h3>
    <p>
      I started at Missouri State University in 2019 majoring in Accounting.
      However, after taking IT classes I decided to pursue a double-major in
      both Accounting and IT Infrastructure. I will be graduating from MSU with
      two bachelor's degrees in the Fall semester of 2023.
    </p>
  </div>
  <div class="subsection">
    <h3 class="subsection-title">Relevant Coursework</h3>

    <div class="coursework-container">
      <CourseworkCard
        name="Intermediate Accounting I"
        description="I have completed the two introductory accounting courses offered at MSU: Financial 
        Accounting and Managerial Accounting. Intermediate Accounting I is the first major-specific course 
        in the Accounting degree program that I have completed. This involved an in-depth look into the 
        financial statements, time value of money, inventory methods, cash and cash equivalents, intangibles, 
        and many more accounting concepts. I also completed a project where I worked through the entire 
        accounting-cycle from transactions to journal entries, posting, trial balance, adjusting entries, 
        income statement, retained earnings, balance sheet, and closing entries"
      />
      <CourseworkCard
        name="Database Management Systems Concepts and Design"
        description="This class included an introduction to database management systems, in particular 
        relational databases. In this course I learned how to create Entity-Relationship Diagrams using 
        crows-foot notation. I also learned about the normalization of data, the different normal forms, 
        keys, and all of the expected best practices of managing database management systems. Most importantly, 
        I learned how to use SQL to query data and create databases, including basic data analysis 
        using joins and SQL selectors. Using MySQL I was able to create databases based off of business logic, 
        fill the rows with given information, and query the tables to find specific sets of data."
      />
      <CourseworkCard
        name="Hardware and Operating Systems"
        description="This was my first IT course I had completed. This was a survey of basic IT processes and 
        how computers work. I acquired hands-on experience assembling a computer, replacing components, and 
        navigating the BIOS. This course was taught parallel to the CompTIA A+ exam, so everything expected 
        on the A+ certification was covered in this course. this included the basics of various hardware 
        components, what constitutes an operating system and how they work, I/O devices, basic networking, 
        and many more concepts. I also learned about PowerShell scripting using the Integrated Shell 
        Environment tool. This class introduced me to dozens of IT concepts and processes that I use in 
        my current job everyday."
      />
      <CourseworkCard
        name="Java Programming"
        description="Intro to Java Programming is a class that focuses on the Java programming language and 
        how to effectively utilize Object Oriented Programming. This included a multitude of hands-on activities 
        where I was tasked with converting business logic into executable code. We used Swing to create GUIs for 
        the user, and I even used Swing on my own to create a Snake clone. You can download this project from 
        <a href='https://github.com/marshallshine/Snake-Game' target='_blank'> here </a>and compile and execute 
        on Windows machines with the Java SDK by running the batch file I wrote. Some of the concepts I learned 
        in this class include the basics of programming such as variables, loops, conditionals, input and output, 
        and also more advanced OOP concepts such as creating objects, inheritance, and polymorphism."
      />
    </div>
  </div>
</section>
<section id="experience">
  <h2>Experience</h2>

  <div class="subsection">
    <div class="experience-card">
      <ExperienceCard
        name="Missouri State University College of Business Computing"
        title="IT Support Specialist"
        description="I started working for COB Computing during August of 2021. My job is 
        to provide general IT assistance to faculty and staff at Missouri State. This includes 
        responding to classroom emergencies, where I need to swiftly troubleshoot and fix 
        issues to avoid wasting classtime. I also work on projects throughout the semester such 
        as hardware rollouts, updating at-risk computers, and ensuring classrooms are ready for use. 
        This job has really taken me into the next level in IT where I feel confident as a working 
        professional. Some of the skills I have learned include imaging computers, working with group 
        policies, performing data backups, installing hardware, troubleshooting, and creating meaningful 
        documentation using Jira."
        imgSrc="./msuLogo.png"
        imgAlt="Missouri State University Logo"
      />
      <ExperienceCard
        name="Allied Insurance Agency"
        title="General Assistant"
        description="Allied Insurance is a small family business where I helped my mother not only with 
        basic office tasks but computer related issues as well. I've helped the owner with purchasing 
        and installing new computers and monitors, backing-up data, and recovering data from old 
        machines. I was new to IT when I started working for Allied Insurance, but I quickly learned 
        the most important skill any IT professional can have: using Google. I was able to learn a lot 
        from searching the internet for a solution to the problem then implementing that solution. 
        The best example I can remember is when the owner had a computer that wouldn't boot into Windows. 
        I was able to enter safe mode and recover important files that were left on the desktop. I've 
        also done basic accounting work here such as calculating comissions and payroll for the employees 
        and reconciled bank statements."
        imgSrc="./alliedInsLogo.png"
        imgAlt="Allied Insurance Agency Logo"
      />
      <ExperienceCard
        name="Freddy's"
        title="Team Member"
        description="My first job was at Freddy's where I was a front of house employee. I did things 
        you'd expect from a fast-food job such as cleaning, taking orders, and making custard. Overall 
        I would say there are two important and pertinent things I've learned from working at Freddy's: 
        Cash handling and customer service. Because of my experience at Freddy's I can now handle cash 
        quickly and accurately. I also developed a great customer service attitude, and can effectively 
        handle frustrated clients and customers with ease. "
        imgSrc="./freddysLogo.png"
        imgAlt="Freddy's Logo"
      />
    </div>
  </div>
</section>
<section id="competitions">
  <h2>Competitions</h2>
  <div class="subsection">
    <h3 class="subsection-title">Summary</h3>
    <p>
      I have been participating in academic competitions relevant to my career
      goals since 2019. During high school I competed in FBLA and DECA securing
      places at national competitions. During college I have been participating
      in competitions through the Association of Business Information Technology
      Students (A-BITS) at MSU. Through these competitions I have been able to
      practice my skills in accounting, system administration, and
      cybersecurity.
    </p>
  </div>
  <div class="subsection">
    <h3 class="subsection-title">Competitions I've Participated In</h3>
    <div class="competitions-container">
      <CompetitionCard
        name="Hivestorm"
        description="Hivestorm is a competition sponsored by the Center for Infrastructure 
        Assurance and Security (CIAS). In October of 2021 I competed with two teammates to secure 
        and implement best-practices on &#34;broken&#34; OS images. This included setting 
        password complexity requirements, removing admin privileges from users, removing 
        unauthorized users, installing and configuring firewalls, removing malicious software, 
        and more. Teams are awarded points based on how many issues they fix. I was tasked with an 
        Ubuntu image and a Windows Server 2016 image."
        imgSrc="./hivestorm-logo.png"
        imgAlt="Hivestorm competition logo"
        compLink="https://www.hivestorm.org/"
      />
      <CompetitionCard
        name="National Collegiate Cyber Defense Competition"
        description="NCCDC is another CIAS competition and is in partnership with Raytheon. 
        It focuses more on Cybersecurity, while Hivestorm is more about system administration 
        and best-practices. I have completed a practice run in this competition using Windows 
        Server 2012. Here I helped manage a web-server, where I used IIS to deploy a website for 
        the competition. The actual competition takes place in the Spring of 2022, and I am 
        currently enrolled in a class focused on preparing for this and other competitions."
        imgSrc="./nccdcLogo.png"
        imgAlt="National Collegiate Cyber Defense Competition logo"
        compLink="https://www.nationalccdc.org/"
      />
      <CompetitionCard
        name="Future Business Leaders of America: Business Plan"
        description="During my senior year of high school in 2019 I competed with two teammates 
        to create a 30-page business plan for a potential company we would create. The business 
        report about our made up company &#34;Sipz&#34; awarded us first place in the state of 
        Missouri, and 6th place in national competition. Some of the things I contributed to the 
        project included the creation of financial statements (Income and Cash Flow), a loan 
        amortization, a description of the accounting system, and even the logo design. You can 
        still see our completed project <a href='https://www.fbla-pbl.org/media/2019-Business-Plan-6th-Place.pdf' 
        target='blank'>here</a> on the FBLA website."
        imgSrc="./fblaLogo.png"
        imgAlt="Future Business Leaders of America logo"
        compLink="https://www.fbla-pbl.org/"
      />
      <CompetitionCard
        name="Distributed Education Clubs of America: Accounting Applications"
        description="In the Spring of 2019 I competed at the local, state, and international level for DECA's 
        &#34;Accounting Applications&#34; event. This competition included both a written test and role-playing 
        components where you would have 10 minutes to prepare an answer for an accounting-based situation. 
        Some of these included creating financial statements from trial balances, explaining inventory and 
        depreciation methods, and describing the use and importance of the accounting cycle. I was awarded 
        2nd place in Missouri, and I was a <a href='https://www.deca.org/wp-content/uploads/2021/09/DECA-HS-ICDC-Winners-2019.pdf#page=19' 
        target='blank'>top 20 finalist</a> at internationals."
        imgSrc="./DECA-logo.png"
        imgAlt="Distributed Education Clubs of America logo"
        compLink="https://www.deca.org/"
      />
    </div>
  </div>
</section>
<section id="skills">
  <h2>Skills</h2>
  <div class="subsection skills">
    <div class="skills-column">
      <h3 class="subsection-title" style="text-align: center">Hard Skills</h3>
      <div class="skills-container">
        <SkillsList
          name="Microsoft Office Applications"
          description="Certified Microsoft Office Specialist (MOS) in Excel and Word. 
        Frequently use Excel, Word, Outlook, and PowerPoint"
        />
        <SkillsList
          name="MySQL"
          description="Querying and creating databases using MySQL"
        />

        <SkillsList
          name="Java and Python"
          description="Application development using Java and Python. More experience in Java, 
        but still have worked using Python"
        />
      </div>
    </div>
    <div class="skills-column">
      <h3 class="subsection-title" style="text-align: center">Soft Skills</h3>
      <div class="skills-container">
        <SkillsList
          name="Troubleshooting"
          description="Identifying and replicating issues in order to find the cause and solve 
        the problem. Plenty of experience from IT Support position at Missouri State"
        />
        <SkillsList
          name="Public Speaking"
          description="Practiced public speaking since 2015 in high school speech and debate 
        club. Continued practicing through college with presentations and collegiate competitions"
        />
        <SkillsList
          name="Teamwork"
          description="Highly capable on cross-functional teams. Experience working in teams 
        from high school competitions and even more extensively at COB Computing and collegiate 
        competitions such as NCCDC"
        />
      </div>
    </div>
  </div>
</section>

<style>
  h1 {
    text-align: left;
    font-size: 2.5rem;
    font-family: Cormorant Garamond;
    font-weight: 600;
    margin-right: 1rem;
    margin-left: 2rem;
  }
  h2 {
    text-align: center;
    text-transform: uppercase;
    font-family: Cormorant Garamond;
    font-weight: bold;
    font-size: 5rem;
    border-bottom: 1px solid black;
    padding-bottom: 0.5rem;
    max-width: 968px;
    margin: auto;
    margin-bottom: 2rem;
  }
  p {
    text-align: center;
  }

  a {
    color: var(--accent-color);
  }
  li {
    float: left;
    display: inline;
  }
  li a {
    width: 100px;
    text-decoration: none;
    padding-top: 15px;
    padding-bottom: 15px;
    padding-inline: 50px;
    border-bottom-style: solid;
  }
  li a:hover {
    background-color: var(--accent-color);
    opacity: 75%;
    color: white;
    transition: 300ms ease-in;
    border-bottom-color: var(--accent-color);
  }

  .name {
    font-size: 4.75rem;
    font-weight: 900;
    padding-top: 1.5rem;
    display: block;
    text-transform: uppercase;
    letter-spacing: 0;
    text-align: left;
    transition: 300ms ease;
    line-height: 100%;
  }
  .name:hover {
    transform: translateX(10px);
    color: var(--accent-color);
  }
  .flex-container {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    justify-content: space-around;
  }
  .my-picture {
    display: block;
    border-radius: 5%;
    height: 40vh;
    box-shadow: 1px 1px 20px rgb(0 0 0 / 50%);
    transition: border-radius 300ms ease, box-shadow 750ms ease;
  }
  .my-picture:hover {
    border-radius: 0;
    box-shadow: 1px 1px 5px rgb(0 0 0 / 30%);
  }
  .navbar {
    margin-bottom: 50px;
    padding: 15px 0;
    width: max-content;
    border-bottom: 2px solid var(--accent-color);
  }
  .intro-content {
    display: flex;
    justify-content: space-around;
    place-items: flex-start;
    flex-direction: row-reverse;
    max-width: 700px;
    margin-left: 17.5%;
    margin-bottom: 50px;
  }

  .subsection {
    margin-bottom: 2rem;
  }
  .skills.subsection {
    display: flex;
  }
  .skills-column {
    flex: 1;
  }
  .subsection-title {
    font-size: 2rem;
    font-weight: 800;
    margin-bottom: 0.75rem;
  }
  .coursework-container {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: flex-start;
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-basis: 100%;
    flex: 1;
  }
  .competitions-container {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: space-between;
    width: 100%;
    display: flex;
    flex-direction: row;
    flex-basis: 100%;
    flex: 1;
  }
  .skills-container {
    padding-bottom: 0.5rem;
    margin-bottom: 2rem;
  }
  section p {
    text-align: left;
    line-height: 1.2;
  }
  section {
    /* min-height: 100vh; */
    max-width: 968px;
    margin: 5vh auto;
    padding: 1rem;
    width: 95%;
    height: auto;
  }
  #intro-synopsis {
    font-size: 1.5rem;
    line-height: 1.2;
    text-align: center;

    max-width: 968px;
    margin: auto;
    padding: 1rem;
  }

  @media screen and (max-width: 768px) {
    ul {
      visibility: hidden;
    }
    .intro-content {
      flex-direction: column-reverse;
      margin-left: 0;
      margin-bottom: 0;
    }
    .intro-text {
      margin: 1rem 0 0 0;
      text-align: center;
    }
    .name {
      font-size: 3.25rem;
      padding-top: 0.5rem;
      text-align: center;
      font-size: 3rem;
    }
    .my-picture {
      margin: auto;
    }
    h2 {
      font-size: 2.25rem;
    }
    section {
      box-sizing: border-box;
    }
    .skills.subsection {
      display: flex;
      flex-direction: column;
    }
    #intro-synopsis,
    p {
      font-size: 1rem;
      line-height: 1.2;
      text-align: left;
      max-width: 968px;
      margin: auto;
      padding: 1rem;
    }
    .name:hover {
      transform: none;
    }
  }
</style>
