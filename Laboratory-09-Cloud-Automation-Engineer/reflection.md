# Mission Reflection

Automation is very important when you manage hundreds of cloud servers. Doing the same backup or cleanup job by hand every day is slow and easy to forget. One missed backup can cause permanent data loss. With automation, the computer does the work correctly and on time, even at 2:00 AM when no one is watching.

However, automation also has dangers. If you make a small typing mistake inside a script (for example, deleting the wrong folder), that mistake will be repeated on every server the script runs on. On 1,000 servers this can destroy a lot of data in a few minutes. That is why we must test scripts carefully on a small scale first and always keep backups of the scripts themselves.

Writing a Bash script is different from writing a Docker Compose YAML file. A Bash script is a list of commands that the computer executes step by step. Docker Compose is a description of how containers should look and connect to each other. Bash is more like giving direct instructions; Docker Compose is more like drawing a blueprint.

Looking back at my GitHub repository from Laboratory 1 to Laboratory 9, I can see how much I have grown. At the beginning I only knew basic Linux commands. Now I can create infrastructure with Terraform, deploy containers with Docker, secure systems, and automate daily tasks with Bash and Cron. Cloud computing no longer feels like magic — it feels like a set of tools I can control.

The role I enjoyed the most was Cloud Automation Engineer. I like the feeling of writing a script once and then watching the computer do the work for me every night. It is powerful and practical at the same time.
