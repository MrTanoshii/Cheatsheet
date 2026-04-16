<div align="center">
  <a href="https://www.gnu.org/software/bash/"><img src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg" title="Bash" alt="Bash" width="64" height="64"></a>
</div>

## Move

```bash
# Move a file from source to destination
mv FROM/PATH/FILE TO/PATH/FILE

# Move all files from source directory to destination
mv FROM/SOURCE_DIR/* TO/DEST_DIR/

# Move all .txt files from source directory to destination
mv FROM/PATH/*.txt TO/PATH/DEST_DIR/
```

## Remote file sync

```bash
# With SSH and key
rsync -avP -e 'ssh -i LOCAL/SSH/PATH/TO/KEY' root@REMOTE_IP:FROM/PATH/FILE TO/PATH/FILE
rsync -avP -e 'ssh -i LOCAL/SSH/PATH/TO/KEY' FROM/PATH/FILE root@REMOTE_IP:TO/PATH/FILE
```

`-a` stands for archive mode, which preserves symbolic links, file permissions, user & group ownerships, and timestamps.

`-v` stands for verbose mode, which provides detailed output of the transfer process.

`-P` stands for progress and partial, which shows progress during transfer and allows resuming interrupted transfers.

`-e` specifies the remote shell to use, in this case, SSH with a specified key for authentication.

## History

```bash
history

# Clear history
history -c 

# Delete specific line
history -d <LINE_NUMBER>
```

# Tarball

```bash
# Create .tar file
tar -cvf <TAR_FILE> <SOURCE_DIR>

# Create .tar.gz file
tar -cvzf <TAR_GZ_FILE> <SOURCE_DIR>

# Extract .tar.gz file (destination directory is optional, if not specified, it will extract in the current directory)
tar -xvzf <TAR_GZ_FILE> -C <DEST_DIR>
```
