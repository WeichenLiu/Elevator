# Elevator
Run other programs with TrustedInstaller privilege.

Please run this program as Administrator, otherwise the service will not work properly.

`Elevator.exe install target_path arguments_for_target...`

For debug purpose, if the service is installed but doesn't remove itself automatically after elevating target program (which is unlikely to happen), the randomized service name will be logged into "log.txt" file. Find the service name and run:

`Elevator.exe remove service_name`

to remove the service.
