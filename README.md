# SAR
## Synopsis

**SAR** is a project at the Yale Social Robotics lab in the Computer Science Department. The goal of this project is to study changes in children that have ASD (Autism Spectrum Disorder). We will use the use of robots along with advanced visualisation techniques to learn about and positively affect these children.

## Usage

To run the mongodb server, use 
    
    sudo docker run --name mongodb mongo:3.2.4

**Release**

    sudo docker run --link mongodb:mongo -p 80:80 waco001/sar


**Test**

    sudo docker run -v ~/Development/SAR/framework/app:/app --link mongodb:mongo -p 80:80 waco001/sar python /app/Main.py

## Contributors

 - [Abhishek Gorti](http://gorti.me/), Student at Hamden High School <abhishek.gorti@yale.edu>

## License

A short snippet describing the license (MIT, Apache, etc.)
