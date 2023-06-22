
# Take away commands:
- command 1
- command 2
- command 3
---
## 1. Create a new virtual machine
1.1. Go to your "Compute Engine" dashboard in "Google Cloud" and select the desired project.

1.2. Click on "CREATE INSTANCE".

<img src="images-are-used/gcloud-jupyter/1.png" alt="Image Description" width="70%" height="70%">

1.3. Define your virtual machine's name that is distinguishable from others.

1.4. Select a "region" for the virtual machine. As a user from Europe, preferably choose a region from Europe to have a faster connection in the future. Here, we have selected "europe-west4 (Netherlands)".

<img src="images-are-used/gcloud-jupyter/2.png" alt="Image Description" width="70%" height="70%">

1.5. Under the "Machine configuration" section, click on the "GPUs" tab.

1.6. Select "GPU type". Here we selected the "NVIDIA A100 40GB".

<img src="images-are-used/gcloud-jupyter/3.png" alt="Image Description" width="70%" height="70%">

1.7. Under the "Boot disk" section, click on the "CHANGE" button.

1.8. Select the "Operating system". Here we need to select "Deep Learning on Linux".

1.9. Select "Version". Here we need to select "Debian 11 based Deep Learning VM with M109"

1.10. Specify the "Size (GB)". Here we need to specify "100".

1.11. Click on the "Select" button to save and exist.

<img src="images-are-used/gcloud-jupyter/4.png" alt="Image Description" width="70%" height="70%">

1.12. Click on the "CREATE" button at the end of the page.

<img src="images-are-used/gcloud-jupyter/5.png" alt="Image Description" width="70%" height="70%">

1.13. You will see your created virtual machine in the "INSTANCES" tab with a green tick before that.

<img src="images-are-used/gcloud-jupyter/6.png" alt="Image Description" width="99%" height="99%">

1.14. If you see a red exclamation mark, it means your virtual machine is not created. You should try it again or change your configuration and create a new one. Here, I tried it again four times and it was created. 

<img src="images-are-used/gcloud-jupyter/7.png" alt="Image Description" width="99%" height="99%">

1.15. Remember to click on the "STOP" whenever your computation is done or you no longer work on the virtual machine.

1.16. You can rerun the virtual machine by clicking "START/RESUME". If a virtual machine will not available, you need to try this more than one time sometimes.

1.17. Because of selecting GPUs on your virtual machine, you are not able to "SUSPEND" your machine.

1.18. If you need to reset the virtual machine while you have been working there, just click on the "RESET" button.

<img src="images-are-used/gcloud-jupyter/8.png" alt="Image Description" width="70%" height="70%">





```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

```bash
$ git clone https://github.com/username/repo.git
$ cd repo
$ ls -la
```
