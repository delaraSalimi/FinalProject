<h1>Talent Matrix Platform</h1>

Talent Matrix Platform is a modular, web-based project, implemented using PHP (Laravel framework), JavaScript, and MySQL, following the MVC (Model-View-Controller) architectural pattern. The platform serves as a two-sided marketplace for programmers and developers seeking employment, and companies searching for talent.

<h3>Project Overview</h3>

The project comprises three main independent modules:

  <ul>
  <li><b>Landing Page Module:</b> The initial interface of the platform providing an overview of the service.</li>

  <li><b>Developers Module:</b> This is tailored for programmers and developers seeking to improve their skills and find job opportunities. They can create their profiles, practice various programming tasks, and demonstrate their skillset to potential employers.
  </li>
  <li><b>Companies Module:</b> This section enables companies to browse developer profiles, view their completed tasks, and engage with potential hires based on their performance.
  </li>
</ul>
Each module works independently and can be deployed separately.
Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
Clone the Repository

Firstly, you need to clone the repository to your local machine:
https://github.com/delaraSalimi/FinalProject.git

Build and Start the Docker Containers

Each module (landing page, developer, company) has its own Docker container and they need to be built and started separately. Navigate to the directory of each module and run the following commands:
<br>
<br>
docker-compose build<br>
docker-compose up -d<br>

Now, your application should be up and running. Remember, you have to run these commands separately for each submodule.
