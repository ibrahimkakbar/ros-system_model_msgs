cmake_minimum_required(VERSION 3.0.2)
project(system_model_msgs)

# Find catkin and package dependencies.
find_package(catkin REQUIRED COMPONENTS
  message_generation)

# Add message files.
add_message_files(
  FILES
  variable.msg)

# Add service files/
# add_service_files(
#   FILES)

# Generate messages.
generate_messages()

# Set up catkin package.
catkin_package(CATKIN_DEPENDS message_runtime)