# Day 3

Virtual machine

i think in simple terms Virtualization means creating smaller parts logically, which has it's own memory, cpu and other stuff

but the question hit me but why? do we need Virtual machine

as we went through the video i found my answer, if you got a resource, why not use it effectively, rather than using multiple resources, example i have few physical servers with each capacity around 200GB, 200CPU, now i got a task, where i have run 4 apps different physical server, but app just using less storage like 5GB, less CPU like 5, I'm running up 4 physical servers, it's better to use hypervisor to make 4 Vms with 10gb, 10 cpu each in one physical server and turn of other 3, it's cool!