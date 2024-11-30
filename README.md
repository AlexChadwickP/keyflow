# Keyflow

Keyflow is a keyboard-first task manager with Git integration. Inspired by the simplicity of Superhuman, it is designed to help developers stay focused, organized, and in flow, all without touching the mouse. Manage your tasks, sync with Git issues, and navigate everything efficiently through the keyboard.

**TODO: Actually write the README rather than getting ChatGPT to generate a very vague one!**

## Features

- **Keyboard-First Navigation**: Keyflow is fully operable with keyboard shortcuts, making it fast and efficient.
- **Git Integration**: Seamlessly sync with your Git repositories. Convert issues into tasks, manage branches, and more.
- **Task Management**: Create, edit, and prioritize tasks with a clean, simple interface.
- **Command Palette**: Perform any action with a quick command palette, keeping you in flow.

## Tech Stack

- **Frontend**: [SvelteKit](https://kit.svelte.dev/)
- **Backend**: [Rust](https://www.rust-lang.org/) with [PostgreSQL](https://www.postgresql.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)

## Getting Started

### Prerequisites

To get started with Keyflow, you'll need the following installed on your machine:

- [Node.js](https://nodejs.org/) (v16 or later)
- [PostgreSQL](https://www.postgresql.org/)
- [Git](https://git-scm.com/)
- [Rust](https://www.rust-lang.org/)

### Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/yourusername/keyflow.git
   cd keyflow
   ```

2. **Install dependencies**:
   ```sh
   npm install
   ```

3. **Set up the database**:
    - Create a PostgreSQL database named `keyflow`.
    - Run the migration scripts to set up the schema.

4. **Configure environment variables**:
    - Create a `.env` file in the root directory with the following keys:
      ```env
      DATABASE_URL=your_database_url
      GITHUB_CLIENT_ID=your_github_client_id
      GITHUB_CLIENT_SECRET=your_github_client_secret
      ```

5. **Run the development server**:
   ```sh
   npm run dev
   ```

6. **Access the application**:
    - Open your browser and navigate to `http://localhost:3000`.

## Usage

- **Command Palette**: Press `Ctrl+K` to open the command palette.
- **Create Task**: Use the command palette or press `N` to create a new task.
- **Navigate**: Use `Tab` and `Enter` to navigate through the application seamlessly.

## Contributing

Contributions are welcome! To get started:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please make sure your code is well-tested and follows the project's style guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by [Superhuman](https://superhuman.com/).
- Built with passion for developers who want to stay productive and focused.
