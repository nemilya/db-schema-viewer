# DB Schema Viewer

DB Schema Viewer is a simple and interactive web application designed to visualize and explore database schemas. It's optimized (at the moment) to work with ActiveRecord schemas, commonly used in Ruby on Rails applications. This tool allows you to import, navigate, and inspect the relationships between tables in a concise, visually appealing format.

## Features

- **Theme Toggle:** Easily switch between day and night modes to suit your viewing preferences using the "Switch to Night/Day Mode" toggle.
- **Schema Import:** Paste an ActiveRecord schema or provide a schema URL to automatically generate and visualize the database structure.
- **Table Navigation:** View all tables in your schema and explore relationships between them, including tables that reference or are referenced by the selected table.
- **Search Functionality:** Quickly locate specific tables using the search bar.
- **Interactive Interface:** Mouse over tables and columns to highlight foreign key relationships.

## Demo

Experience the DB Schema Viewer in action: [Live Demo](https://nemilya.github.io/db-schema-viewer/)

## Getting Started

To start using the DB Schema Viewer locally, simply download or clone the repository and open `index.html` in your preferred web browser.

## Installation

- **Clone the repository:**
   
   ```bash
   git clone https://github.com/nemilya/db-schema-viewer.git
   ```

- **Navigate to the directory:**

   ```bash
   cd db-schema-viewer
   ```

- **Open `index.html`:**
    
Double-click on the `index.html` file or open it with your browser to launch the viewer.

## Usage

1. **Import a Schema:** Click the "Import" button. You can either paste your ActiveRecord schema into the provided text area or enter a schema URL. Hit "Do Import" to visualize the schema.
    
    - **Example:** Use a URL to automatically load the schema, such as:  
        [View Mastodon Schema](https://nemilya.github.io/db-schema-viewer/index.html?schemaUrl=https://raw.githubusercontent.com/mastodon/mastodon/main/db/schema.rb)

2. **Explore Tables:** Use the interface to click on tables and view related tables and columns. You can return to all tables view by clicking the "Return to All Tables" button if you've selected a particular table.
    
3. **Search Tables:** Use the search bar to find specific tables quickly.
    

## Contributing

We welcome contributions! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is open-source and available under the `MIT License`.

## Feedback

For issues, questions, or suggestions, please open an issue on the [GitHub repository](https://github.com/nemilya/db-schema-viewer/issues).
