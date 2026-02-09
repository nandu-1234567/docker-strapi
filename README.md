<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Strapi Docker Setup – Step by Step</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.7;
            color: #2c3e50;
        }
        h1, h2 {
            color: #1a5276;
        }
        ul {
            margin-left: 25px;
        }
        hr {
            margin: 30px 0;
        }
    </style>
</head>
<body>

<h1>Run Strapi Application Locally Using Docker</h1>

<p>
This document explains how to containerize and run a Strapi application locally using Docker.
Each step is explained clearly without technical commands.
</p>

<hr>

<h2>Step 1: Install Docker</h2>
<ul>
    <li>Download and install Docker Desktop on your system.</li>
    <li>Start Docker after installation.</li>
    <li>Ensure Docker is running properly before continuing.</li>
</ul>

<hr>

<h2>Step 2: Prepare the Strapi Application</h2>
<ul>
    <li>Create or use an existing Strapi application.</li>
    <li>Open the Strapi project folder on your system.</li>
    <li>Confirm that the project contains configuration, source, and public folders.</li>
</ul>

<hr>

<h2>Step 3: Add Docker Support</h2>
<ul>
    <li>Create a Docker configuration file in the root of the Strapi project.</li>
    <li>This file defines the runtime environment for the application.</li>
    <li>It also specifies how dependencies are installed and how Strapi starts.</li>
</ul>

<hr>

<h2>Step 4: Ignore Unnecessary Files</h2>
<ul>
    <li>Create a file to exclude unnecessary local files from the Docker image.</li>
    <li>This prevents copying dependencies, cache files, and version control data.</li>
    <li>This step helps reduce image size and build time.</li>
</ul>

<hr>

<h2>Step 5: Build the Docker Image</h2>
<ul>
    <li>Use Docker to create an image from the Strapi project.</li>
    <li>Docker will install dependencies and prepare the application.</li>
    <li>Wait until the image build process completes successfully.</li>
</ul>

<hr>

<h2>Step 6: Run the Strapi Container</h2>
<ul>
    <li>Start a container using the built Docker image.</li>
    <li>The container will run the Strapi application internally.</li>
    <li>The Strapi service will be exposed to your local machine.</li>
</ul>

<hr>

<h2>Step 7: Access the Application</h2>
<ul>
    <li>Open a web browser.</li>
    <li>Access the Strapi Admin Panel using the local address.</li>
    <li>Complete the admin user setup if it is your first time.</li>
</ul>

<hr>

<h2>Step 8: Stop the Application</h2>
<ul>
    <li>Stop the running container when you no longer need the application.</li>
    <li>This will shut down the Strapi service safely.</li>
</ul>

<hr>

<h2>Important Notes</h2>
<ul>
    <li>Strapi uses a local database by default.</li>
    <li>Data will not persist if the container is removed.</li>
    <li>For production environments, an external database is recommended.</li>
</ul>

<hr>

<h2>Completion</h2>
<p>
You have successfully containerized and run a Strapi application locally using Docker.
</p>

<p><strong>Done 🎉</strong></p>

</body>
</html>

