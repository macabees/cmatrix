# CMatrix
Displays the scrolling lines from 'The Matrix' movie. 

Press 'q' to quit.

## CMatrix (Project Info)
[Website](https://www.asty.org/cmatrix/)

## Docker Hub
[Website](https://hub.docker.com/r/macabees/cmatrix/)

## Build image
`$ docker build -t macabees/cmatrix:latest .`

## Run image
`$ docker run -it --rm macabees/cmatrix`

Display scrolling text in different colors 
`$ docker run -it --rm macabees/cmatrix -C [green|red|blue|white|yellow|cyan|magenta|black]`

## Help
`$ docker run -it --rm macabees/cmatrix --help`
