# hello-world-python-rest

### Build the container
`docker build -t adanlessossi/hello-world-python-rest:0.0.1.RELEASE .`

### Run the container
`docker run -d -p 5000:5000 adanlessossi/hello-world-python-rest:0.0.1.RELEASE`

#### Test the container
`http://localhost:5000/`

### Push the image
`docker push adanlessossi/hello-world-python-rest:0.0.1.RELEASE`
