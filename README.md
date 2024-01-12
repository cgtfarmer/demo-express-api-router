# Getting Started

### Installation

1. Clone this project
1. Run: `docker-comopse run web npm install`
1. Run: `docker-compose up -d` to bring up container(s)
1. Run: `docker-compose logs -f` to tail logs
1. Navigate to `http://localhost:3000` in your browser

### Development

Not all code changes will be automatically recognized, so you'll need to restart the stack:

Run: `docker-compose down; docker-compose up -d; docker-compose logs -f`
