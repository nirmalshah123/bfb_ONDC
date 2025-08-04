# bfb_ONDC
sparse Matrix | Build For Bharat | Team - Vanarsena (Nirmal Shah ,  Lyric Khare)

### Presentation Link
https://drive.google.com/file/d/1O-B7HA8brQXu5_e_8qazXYWtSHUBLm2H/view?usp=sharing

### Cloud Service link (POC)
https://sample-vz7453572a-el.a.run.app/docs

### Presentation Video Link
https://drive.google.com/drive/folders/1TmoPUck75EVsURyV7Qi9P7y2ltby5U3G?usp=drive_link



## Quick-Start
```
pip install fastapi
pip install python-multipart
pip install uvicorn
```

## Executable
In fastAPIExec, Run the following command to start the uvicorn server
```
uvicorn app:app --host 0.0.0.0 -port 5000
```

In the browser, to open swagger interface, go to the following address

> 0.0.0.0:5000/docs


## To use API

In testingAPI/test.ipynb;

> _requests_ library is used to send and receive data

> Utilize test.ipynb to get helper functions to get and set the data from HTTP requests

> parallel curl.txt contains commands to send parallel curl requests


## DockerGCP
This folder contains file system to generate a docker image or to deploy to google cloud platform.

To deploy as "Cloud Run Service"

```
gcloud run deploy <ServiceName> --port 8080 --source .
```


