Here you find a link and a short description of some test task I did before (you may complain that names of repositories are rather
cryptic and README files are brief and you're right and in fact that's for purpose as employers obviously don't like
the answers for their test tasks be publicly available and by giving them (repos) vague names I make it more difficult for
some random people finding my projects by googling)
Unfortunately, I have almost no any production code suitable to be published as a portfolio. This is why here you can see mostly test tasks. The production
code I've been worked on either can not be shared as should accord NDA or just makes no sense without some datasets which I'm also not permitted to show 
to everyone as containing some private data:

- https://github.com/bearsandtigers/video_archive_django_celery_k8s
see some description in the README.md. Basically, the task was to:
1. Develop a simple application with Django and Celery so it able to receive video files (or links to) from users and process those files asynchroniously.
2. Prepare YAML files to deplot the app to k8s.

- https://github.com/bearsandtigers/positions_extractor -
extracts interesting for me vacancies (by keywords) from https://hh.ru (Russian largest headhunters site), demonstrates async scrapping in Python.

- https://github.com/bearsandtigers/appcenter-api-python-test-task -
the task was to implement script to automaticaly run builds for a some MS Appcenter application - nothing special,
but I had to implement on my own some methods for working with branches and builds as the module I used as a basis lacks them.

- https://github.com/bearsandtigers/repo-test-task -
the task was to write simple playbook which downloads Peervpn sources, builds binary file, makes deb package containing it and
publishes the deb package in a self-hosted repo so the created Peervpn package can be installed in the specified Ubuntu versions.

- https://github.com/bearsandtigers/stream-capture-test-task -
deploys a couple of simple containers with ffmpeg and Nginx inside them where the former constantly captures a screenshot from online
streaming video and the latter publishes it for the web.

- https://github.com/bearsandtigers/drf-test-task -
this project is for https://www.rivermeadow.com. It seems they asked some Russian company to find remote programmers for them in Russia.
I had to disclose company name here as I think that if you have a look at their site it will much easier for
you to understand what this task should do then if instead I were trying to explain its essence using my poor English :-)

- https://github.com/bearsandtigers/terraform-mongo-rs -
first, uses Terraform to deploy several virtual machines (in Yandex Cloud) and then with Ansible deploys simple MongoDB cluster in them

Please don't judge strictly those projects as, let me repeat again, most of them are just test tasks performed in a hurry and definitely not production-ready.
Thank you for your attention.
