# htop running on Centos7

This container contains htop running on a Centos7 base.  

To run this container execute the following:  

        docker run -it --rm \  
          --pid host --rm \  
          docker.io/hvindin/centos7-htop:latest
