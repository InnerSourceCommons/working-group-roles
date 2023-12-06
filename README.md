# Working Group Roles

This repo provides a [Jekyll theme](https://jekyllrb.com/docs/themes/) that helps you to generate a documentation page describing roles to use to run your working group meetings.
Multiple working groups in the InnerSource Commons have found these roles to be a useful way to distribute the tasks associated with running meetings of the working group.
Distributing this work makes the load easier for each person, spreads knowledge about running the group to multiple people, and keeps multiple people engaged and interested in the working group.

In just a few minutes, you can have documentation pages up that describe how to perform the following roles:

* **Scheduler**.
The person that sets up the calendar invite and meeting agenda.
* **Crier**.
The person that reminds people in _Slack_ of the upcoming meeting.
* **Facilitator**
The person that conducts the group through the agenda during the meeting.
* **Scribe**
The person that takes attendance, notes, and assigmments during the meeting and shares these afterwards.

## Getting Started

1. Copy [the contents of _config.yml](https://raw.githubusercontent.com/InnerSourceCommons/working-group-roles/master/_config.yml) into the `_config.yml` in the root of your working group repo.
1. Replace the placeholders in the file with text specific to your working group.
1. Copy all the files in the [/roles](/roles) directory of this repo into the `/roles` directory of your working group repo.
1. Set up GitHub pages to deploy your site from the main branch.

![image](https://user-images.githubusercontent.com/9609562/220431948-2b362022-7d6f-47d5-b211-6a1811509ada.png)

Your roles documentation site should be live at https://innersourcecommons.github.io/your-working-group/!

## Contributing

* Prefer asterisk formatting of lists rather than hyphen formatting.
See [this discussion](https://nickang.com/2018-03-05-markdown-bullet-points-hyphen-asterisk/).
* Write each new sentence on a new line.
GitHub allows leaving comments on a line-by-line basis.
Reviewing and commenting the submitted text is much easier if there are multiple lines on which to leave comments.
Sentences on consecutive lines will be collapsed into a single paragraph (like this one) in the final rendering of the content.

### Developing 

To test your changes to the theme locally, you can preview the theme using the same command used to preview a Jekyll website:

```bash
# install the dependencies 
bundle install

# serve the website with jekyll
jekyll serve
```

If you have an environment able to run containers that is compatible with _Docker Compose_ (e.g. Docker Desktop or Podman), run the website locally with the following command:

```bash
docker compose up
```

You should be able to access the website at <http://localhost:4000>.