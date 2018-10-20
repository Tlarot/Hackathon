# Hackathon

1. Download and install Docker and create a Docker account ([link](https://www.docker.com/get-started)).

2. Fork this repository to your GitHub repo and clone it (do not push changes to this repository).

3. Run docker (mount the repository folder, or where you will download your datasets):

```
docker run -p 8888:8888 -v /your/local/dev/folder:/home/jovyan -v /another/host/dev/folder:/home/jovyan/downloads jupyter/datascience-notebook
```

4. Get the link to jupyter notebook with token, e.g.

```
http://127.0.0.1:8888/?token=19a139f342747af2e3f691f0966f88a70a0393832f65cb8f
```

5. Check if you see your host folders mounted and if you can create new notebooks

6. Start hacking, your datasets are in `dataset/kudos.csv` and `dataset/employees.csv`!
