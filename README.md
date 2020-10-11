![Hactoberfest 2020](/assets/hacktoberfest2020.svg)

# IT Memes

This repo was created for beginners looking to contribute to [Hacktoberfest 2020](https://hacktoberfest.digitalocean.com/) in a fun way. 

This repo is the backend to the webpage [www.nickneos.com/IT-Memes](https://www.nickneos.com/IT-Memes/) - a page with light hearted IT related memes 😃


## Contributing

To submit an IT meme to [www.nickneos.com/IT-Memes](https://www.nickneos.com/IT-Memes/) you will need to raise a Pull Request.

PR's to this repo will count towards the 4 PR's needed to score a free Hactoberfest t-shirt 😎

1. Make sure you have a github account (obviously) and sign up to Hactoberfest [here](https://hacktoberfest.digitalocean.com/) if you haven't already.
2. Fork this repo.
3. Clone the forked repository locally
    ```yaml
    git clone https://github.com/<USER_NAME>/<REPO_NAME>
    ```
4. Add you're meme image to the `assets/memes/` directory.
5. Open `_pages/index.md` and copy the last block of `yaml` code that looks like this:
    ```yaml
    # insert image details below (spacing important!)
    - url: /assets/memes/sql_programmers.jpg
      image_path: /assets/memes/sql_programmers.jpg
      # short description of image
      alt: SQL Programmers
      # your name and github page
      title: Posted by [Nick Neos](https://github.com/nickneos)
    ```
5. Paste it underneath the one you copied. Make sure indentation and spaces line up exactly like the others as this is important with `yaml`.
6. Edit `url` and `image_path` with your image path; edit  `alt` and `title` accordingly as per the comments.
7. Save index.md and commit and push your changes:
    ```bash
    git add .
    git commit -m "SHORT DESCRIPTION OF CHANGE"
    git push
    ```
8. Go to your forked repo in GitHub, and raise a pull request to this repo.
9. Once merged it should count towards your 4 PR's which you can keep track of [here](https://hacktoberfest.digitalocean.com/profile).

## Credit

* Webpage theme: [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes)
* Idea for the meme page: [ProjectDock](https://github.com/ProjectDock/programming-memes)