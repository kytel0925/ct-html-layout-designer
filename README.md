## Installation

### Requirements

In order to develop on this project please ensure that your machine fulfill the following requirements:

- [Git](https://git-scm.com/doc).
- [Docker](https://docs.docker.com/engine/install/) with [docker compose plugin](https://docs.docker.com/compose/install/).

### Steps

- [Clone the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
- create a .env file <code>cp .env.example .env</code> _tune any variable as you wish_
- Boot the project with <code>docker compose up -d</code>
- Start developing

Now enter into your [app](http://localhost) and you should a hello world page

## Evaluation

### Part 1: Build html files for each image inside the designs folder

- The html and css must be on the same file
- Build the html structure as the image suggest
- All text elements must be present and SHOULD NOT BE an image
- The banners MUST BE images
- Name each file according as the design image, for example design-1.jpg = design-1.html

### Part 2: Test each html files to see how good it renders in email clients
- The clients that we except are: gmail, outlook (web), yahoo
- We except and score above 60%
