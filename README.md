# pipenv
- Install pip
```bash
sudo apt-get install python3-pip
```

- Install pipenv
```bash
pip3 install pipenv
```

- If you see this message, this shows pipenv is saved in another folder which is not in the PATH

![Screenshot 2024-02-25 153711](https://github.com/sshuen30/pipenv/assets/40738215/f6d2e7a4-99f7-41fc-b0e6-f805ac50ce28)

- To see your current path
```bash
echo $PATH
```

- Add the folder to PATH by running this command
```bash
export PATH="/home/kasm-user/.local/bin:$PATH"
```

- To make this persistent after reboot, add the above command into the EOL of the ~/.bashrc
```bash
sudo nano ~/.bashrc
```

- To run pipenv, cd to your project folder and type this command
```bash
pipenv shell
```

- You have created a virtual environment
