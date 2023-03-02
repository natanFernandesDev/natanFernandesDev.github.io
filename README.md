
# Website ⭐

> A simple and cool retro styled website, built to showcase my content and projects.

## 📋 Requirements

- [Ruby 2.7.6](https://www.ruby-lang.org/)
- [Bundler 2.3](https://bundler.io/)

## 🔎 Usage

1. Clone the repo to your machine.

3. Update dependencies gems with:

    ```console
    bundle install
    ```

3. Start the local server to preview your changes:

    ```console
    bundle exec jekyll serve
    ```

4. Push your changes to your repo and wait for the GitHub Actions to finish the build and deployment to GitHub Pages.

## 🚀 Deploy

You can find the GitHub Actions workflow file on `.github/workflows/main.yml`, this file contains everything about it, but it basically uses of `helaili/jekyll-action@v2` action from the marketplace to build and deploy to the `gh-pages` branch of the repo.

If you want to use it:

1. Make sure you have selected `Read and write permissions` on `Settings > Actions > General > Workflow permissions`, so the action can push the generated static site files to the `gh-pages` branch.

2. Enable GitHub Pages on `Settings > Pages`, selecting `gh-pages` as your source branch.

Bonus, if you want to use a custom domain:

1. Verify it on `You Account Settings > Pages`, click on `Add Domain` and just follow the instrusctions.

2. As finishing it, just add the following GitHub's records to your DNS provider configuration:

    A records:
    ```
    185.199.108.153
    185.199.109.153
    185.199.110.153
    185.199.111.153
    ```

    AAAA records:
    ```
    2606:50c0:8000::153
    2606:50c0:8001::153
    2606:50c0:8002::153
    2606:50c0:8003::153
    ```

You can find more information on the [official documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#about-custom-domain-configuration).

## 📋 Issues

Feel free to open an issue if you find a bug or have a suggestion, so we can discuss the best way to improve or fix it.

## 👋 Contributing

You're always welcome to contribute to this project, just create your pull request, and wait for the review.

## 📜 License

This project is made under the MIT license, for more information about its possible use, modification, and sharing, [click here](LICENSE).
