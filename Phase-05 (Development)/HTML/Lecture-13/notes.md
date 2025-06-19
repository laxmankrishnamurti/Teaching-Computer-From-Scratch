# How to download Libre Office in Ubuntu?

- [Go to the website](https://www.libreoffice.org/download/download-libreoffice/)
- Choose the appropriate Operating System and the package that your system accept. 
- Click on download. 
- Now, we have the file named : _LibreOffice_25.2.4_Linux_x86-64_deb.tar.gz_

# How to extract that file and install it on our local system ?

We don't have the .deb package. So, what next ?

First of all we have two kind of extensions in that file. 

- .tar stands for Tar.  
- .gz stands for Zip.

### **`What is a Tar file ?`**

It is a wonderful technology used to combine multiple files into a single executable file. 

**How to extact it?**

```bash
# <> : Escape the sign
tar -xzvf <file_name>
tar -x -z -v -f <file_name>

# sudo apt install -y (Prompting : It is a process that system uses to ask some questions from the sudo user {That have sudo privileges}.)
```

### **`How to install multiple .deb package with a single cmd`**


```bash
sudo dpkg -i *.deb

# *.deb : I don't care about the file name. We explicitly states that you just have to install all .deb packages. 
```

**`Caution : .deb package should exit in your PWD.`**