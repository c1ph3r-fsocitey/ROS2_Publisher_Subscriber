

# ROS2 Humble Publisher and Subscriber

This repository contains a basic implementation of a ROS2 publisher and subscriber. The publisher simulates a news station publishing news to a radio station, and the subscriber simulates a smartphone subscribing to the news radio topic.

## Prerequisites

To use this code, you will need to have ROS2 installed on your system. Follow the instructions on the ROS2 website to install ROS2: https://docs.ros.org/en/foxy/Installation.html

## Usage

1. Clone the repository to your local machine:
   ```
   git clone [https://github.com/YOUR-USERNAME/ros2-news-pub-sub.git](https://github.com/c1ph3r-fsocitey/ROS2_Publisher_Subscriber.git)
   ```
2. Build the workspace:
   ```
   cd ros2-news-pub-sub
   colcon build
   ```
3. Open a terminal and source the ROS2 setup script:
   ```
   source /opt/ros/foxy/setup.bash
   ```
4. Start the ROS2 master:
   ```
   ros2 run ros2_news_pub_sub ros2_news_pub_sub
   ```
5. Open a new terminal and source the ROS2 setup script:
   ```
   source /opt/ros/foxy/setup.bash
   ```
6. Start the subscriber:
   ```
   ros2 run ros2_news_pub_sub ros2_news_subscriber
   ```
   
You should now see the news being published by the publisher and received by the subscriber.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
