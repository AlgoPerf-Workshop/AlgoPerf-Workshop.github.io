# Website of the AlgoPerf 2025 Workshop

This is the repository for the "AlgoPerf Workshop" 2025.

## Contributing

Feel free to suggest changes or extensions to the website by opening pull requests or by opening an issue.

### Locally Building the Website

1. Fork the repository and clone it to your local machine.

   ```bash
    git clone https://github.com/AlgoPerf-Workshop/AlgoPerf-Workshop.github.io
    cd AlgoPerf-Workshop.github.io
   ```

2. Install `Jekyll` following the instructions [here](https://jekyllrb.com/docs/installation/)
3. Install the required dependencies and plugins for the site via:

   ```bash
   cd docs
   bundle install
   ```

4. You can now locally build the website and see your changes in real-time:

    ```bash
    bundle exec jekyll serve --livereload --open-url
    ```
