# C
Create a class Device with the following attributes

⚫_device_id which is a string value

⚫_device_type which is either INFOTAINMENT, ACCESSORY or SAFETY.

_device_battery_level which must be an integer value between 1 to 100.

_device_driver which is a shared_pointer to an instance of type Device Driver.

A function to find_battery_drain_factor which returns a float value based on the following conditions

• If Device is of_device_type INFOTAINMENT or SAFETY, value should be 0.25

• If Device is of_device_type SAFETY, value should be 0.5 if current _device_battery_level is above 50 else it should be 0.4

Create a class Device Driver with the following attributes

_version_number which is a string value.

_release_quarter which could be Q1, Q2, Q3 or Q4.

_size_in_bytes which is a float value.

Create the following functionalities in a functionalities.cpp file (with a suitable header file)

• A function to create 5 instances of Device type on the hea using shared_ptr.

A function to find and return the_device_id of all instances in a container which return _battery_drain_factor of above 0.3

A function to check if all Device instances are of_device_type INFOTAINMENT or not.

A function to return the average_size_in_bytes for instances whose_release_quarter is either Q1 or 04.

• A function to find and return the_version_number of the Device Driver for the instance

whose_device_id matches with the id value provided as a parameter to the function. • A function to find the Device Driver instances whose type match with the type provided as the second parameter to the function and return such instances in a container.

Demonstrate each functionality by creating the suitable Main file (client code)
