# Lista

An application dedicated to tracking reading materials by chapters and volumes!

One of my first projects trying to solve one of my everyday nitpicky problems of trying to keep a place on tracking my manga and light novels and what chapter or volume I'm on at!

## Technical Details
This project is created with:
* Ruby 4.0.5
* Rails 8.1.3
* PostgreSQL 17

The developer has made this project with these system specifications and dependencies:
* macOS 15 Sequoia
* Node.js & npm
* Yarn (for managing packages and building the Custom Bootstrap configuration)
* mise
	* Ruby
	* PostgreSQL
	* Node.js
	* Yarn

The project makes use of:
* Bootstrap 5 & Bootstrap Icons (compiled via sass and postcss-cli using Yarn)
* JS Bundling via esbuild
* Solid Cache, Solid Queue, Solid Cable (Rails 8 defaults)

## Getting Started

### Prerequisites
Make sure you have Ruby 4.0.5, PostgreSQL 17, Node.js, and Yarn installed on your system.

### Installation
1. Clone the repository and navigate into the project directory:
   ```bash
   cd lista8
   ```

2. Install the required Ruby gems:
   ```bash
   bundle install
   ```

3. Install the JavaScript and CSS dependencies:
   ```bash
   yarn install
   ```

4. Create and set up the database:
   ```bash
   bin/rails db:prepare
   ```

### Running the Application
To run the Rails server along with the Javascript and CSS compilation watchers:
```bash
bin/dev
```
