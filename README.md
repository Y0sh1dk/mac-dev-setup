# Mac Dev Setup

This repository contains a Ansible playbook and configuration files to automate the process of boostrapping a new MacOS development environment.

The playbook has been tested on a 2021 M1 MacBook Pro, running Ventura 13.3 and is being constantly updated as changes are made to my development environment.

It is heavily inspired by [geerlingguy/mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook).

## Usage

To use this playbook for the first time:

1. Ensure xcode CLI tools are installed

   ```
   xcode-select --install
   ```

2. Create main code directory

   ```
   mkdir ~/Code
   ```

3. Clone repository

   ```
   cd ~/Code
   git clone https://github.com/Y0sh1dk/mac-dev-setup.git
   ```

4. Run boostrap script
   ```
   ./bin/boostrap
   ```

To run this playbook again:

1. Run the playbook
   ```
   cd ~/Code/mac-dev-setup
   ./bin/run
   ```

## Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
