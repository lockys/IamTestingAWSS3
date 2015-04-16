##initial bash script
    
    #!/bin/bash  
    sudo yum install -y ImageMagick
    sudo easy_install argparse
    mkdir /home/ec2-user/jobs
    sudo git clone https://github.com/lockys/IamTestingAWSS3.git /home/ec2-user/img-process
