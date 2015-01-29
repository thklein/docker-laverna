# docker-laverna

[Laverna](http://laverna.cc) is a note taking web application written in JavaScript. It's built to be an open source alternative to Evernote. This is a [Docker](https://docker.com) image that eases setting up to host Laverna on your own server.

## About

> *From the official [website](http://laverna.cc):*

Why should you use Laverna as note taking application?

* **No registration required:**
Laverna is a web app written in JavaScript which means it requires no installation and no registration.
* **Encryption:**
Laverna can encrypt all your notes on client side with SJCL library and no one, except you, can get access to them.
* **Markdown:**
Laverna web app uses pagedown and ACE editor. Also we support several editing modes: distraction-free mode, preview mode and normal.
* **Privacy:**
None of us can get access to your personal data because we are using IndexedDB and localStorage. In fact all your information will be stored only on client-side.
* **Synchronizing:**
In settings page you can enable synchronizing with cloud storage. After that all your information can be accessed from anywhere.
* **Tasks:**
Application also supports tasks. Adding tasks as easy as in GitHub. 

## Getting the container

The image is available as a [trusted build on the docker hub](https://registry.hub.docker.com/u/thklein/laverna/):

```bash
$ docker pull thklein/docker-laverna
```

## Using the container

You can launch the container using the docker command line,

```bash
$ docker run -d -p 80:80 thklein/docker-laverna
```
and finally point your webbrowser to:

```bash
http://localhost/laverna
```
