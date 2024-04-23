TCHA

Step 1 : ```docker build -t tcha .```

Step 2 : ```docker run -v /mnt/DATA/TCHA:/TCHA -ti --rm tcha /bin/bash -c ". /opt/miniconda/bin/activate; cd /TCHA/tcrm; python main.py"```
