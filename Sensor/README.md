<!-- ABOUT THE PROJECT -->
## IoT Air Quality Monitoring Sensor
![Overview](Img/design.pdf)
![Case Design](Img/top.jpg)
![Hardware](Img/actual.jpg)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* Adruino IDE 2.3.4

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Adruino IDE
* Configure the MCU
* PubSubClient 2.8.0
* DFRobot_ENS160 1.0.1
* [AHTxx](https://github.com/enjoyneering/AHTxx) as external library 

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

2. Clone the repo
   ```sh
   git clone https://github.com/Shin4017/IoTSensor.git
   ```
3. Install required packages
  
4. Enter configuration information
   ```js
   const  char* ssid = "Wi-Fi SSID Name"
   const  char* password = "Wi-Fi Password"
   const  char* mqtt_username = "Username for MQTT broker"
   const  char* mqtt_password = "Passord for MQTT broker"
   const  char* outTopic = "Topic to publish data"
   const  char* inTopic = "Topic to subscribe data"
   const  char* clientID = "unique client id for MQTT broker"
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Add PM2.5 Sensor
- [ ] Create GUI to put config information
- [ ] Add Additional Sensors

<p align="right">(<a href="#readme-top">back to top</a>)</p>
