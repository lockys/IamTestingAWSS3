##initial bash script
    
    #!/bin/bash  
    sudo yum install -y ImageMagick
    sudo easy_install argparse
    mkdir /home/ec2-user/jobs
    wget -O image_processor.py https://raw.githubusercontent.com/lockys/IamTestingAWSS3/master/image_processor.py
    
## check out the fucking process if exit or not

    ps -fa | grep image_processor.py
