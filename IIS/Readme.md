If you want to build docker image for IIS in Windows 10, you need to switch the docker desktop mode into Windows Container mode.
Then, run "docker build -t iis ." and "docker run -d -p 8080:80 --name www iis:latest.
Use your web browser to see the result : http://localhost:8080
