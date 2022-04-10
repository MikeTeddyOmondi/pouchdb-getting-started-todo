# PouchDB "Getting Started" Todo app (complete)

A complete version of the ["Getting Started"](http://pouchdb.com/getting-started.html) PouchDB todo app.

To check out the code as a Git repository, run this in your shell (without the `$`):

    $ git clone https://github.com/MikeTeddyOmondi/pouchdb-getting-started-todo.git

Or to simply download a zip file, click the **Download ZIP** button to the right.

# Containerised w/ NGINX

Docker image: [ranckosolutions/todo-app-web:latest](https://hub.docker.com/repository/docker/ranckosolutionsinc/todo-app-nginx/)

# Deploying on Kubernetes:

```bash
kubectl apply -f web-depl.yml
```

You will now be able to connect to the nginx server on http://localhost:30001.

> Helm charts comming soon!...
