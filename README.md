# dockerfile-multistage
Demonstrates the benefit of using multistage Dockerfile on image size
- Dockerfile : uses two stages to build the image, using the compiled version of the "go" program
- Dockerfile.singlestage : uses only one stage to compile and run the "go" program
