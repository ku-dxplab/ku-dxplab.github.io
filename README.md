# 2024 HCI Course Website

This website for the 2024 Human-Computer Interaction (HCI) course at Korea University is developed using the [Just the Class](https://github.com/kevinlin1/just-the-class) template, which extends the [Just the Docs](https://github.com/just-the-docs/just-the-docs) theme. The site serves as a comprehensive resource for students, providing announcements, course schedules, staff information, and more.

## Local Development

To build and run the site locally, you'll need to have [Jekyll](https://jekyllrb.com/) installed. Follow the official Jekyll documentation for installation instructions [here](https://jekyllrb.com/docs/installation/).

Once Jekyll is installed, you can serve the site locally with the following command:

```shell
$ bundle exec jekyll serve
```

## Adding Your Information

- Register your personal information by creating a file in the [`_staffers/`](./_staffers) directory with the format `{name}.md`.
- If your post requires images or media files, manage them within the [`assets/`](./assets) directory.