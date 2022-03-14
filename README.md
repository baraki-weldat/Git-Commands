# Git-Commands
sudo apt  install docker.io

sudo docker pull tensorflow/tensorflow

#### Installing git Version Control in Ubuntu 
```
### Download the github desktop Application 
sudo wget https://github.com/shiftkey/desktop/releases/download/release-2.9.3-linux3/GitHubDesktop-linux-2.9.3-linux3.deb
### Download the github desktop Application 
##### Install gdebi-core before the github desktop
sudo apt-get install gdebi-core 
##### Install the GitHubDesktop Application 
sudo gdebi GitHubDesktop-linux-2.9.3-linux3.deb

```
### Installing Anaconda Notebook in Ubuntu 
### 1. Installing dependencies
```
sudo apt install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6
```
### 2. Downloading the Anaconda 
```
wget -P /tmp https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh
```
### 3. Installing the Anaconda 
```
bash /tmp/Anaconda3-2020.02-Linux-x86_64.sh
```
### 4. Activating the Conda
```
source ~/.bashrc
```
### 5. Launching the Anaconda Navigator
```
anaconda-navigator
```
This command pulls the remote repository into your local computer:
```
git clone https://github.com/baraki-weldat/Question-Answering-for-Tigrigna-Language.git
```
…or create a new repository on the command line
```
echo "# Question-Answering-for-Tigrigna-Language" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/baraki-weldat/Question-Answering-for-Tigrigna-Language.git
git push -u origin main
```
…or push an existing repository from the command line
```
git remote add origin https://github.com/baraki-weldat/Question-Answering-for-Tigrigna-Language.git
git branch -M main
git push -u origin main
```

