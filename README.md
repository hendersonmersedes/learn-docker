# learn-docker
<h2>Docker 101</h2>
<h3>The first thing that you want to do is go to the <b>Docker</b> website to download and install <b>Docker</b></h3>
<br>https://docs.docker.com/desktop/windows/install/</br>
<p>
  <ol>
    <li>Clone the Docker repo using 
      <br><b><i>docker run --name repo alpine/git clone\ https://github.com/docker/getting-started.git docker cp repo:/git/getting-started/</br></b></i></li>
    <li>Build a Docker image for your container: <b><i> cd getting-started docker build -t docker101 tutorial</b></i></li>
    <li>Run a container off the Docker image built: <b><i> docker run -d -p 80:80 \ --name docker-tutorial docker101tutorial</b></i></li>
