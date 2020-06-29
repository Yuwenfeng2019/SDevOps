# SDevOps
An eBPF(https://en.wikipedia.org/wiki/Berkeley_Packet_Filter)-centric，microservices-aware DevOps with the assistance of AI and Security
technologies.

Intergrating serveral open source projects like NetData(https://github.com/netdata) and Cilium(https://github.com/cilium) to achieve our new designs:
    1. Mainly focus on Linux platform with leading-edge eBPF support
    2. A customized NetData version that base on eBPF(NetData has added support for monitoring, troubleshooting, and debugging applications with eBPF
       metrics since their latest 1.23 release) is for system and application cluster monitoring, and more eBPF-centric design will be added in our 
       new implementation here. In addition, further enhancement like a new distributed architecuture is also being considered;
    3. Integrate project Cilium for API-aware Networking and Security that leveraging eBPF/XDP to support microserivces-oriented and containerized 
       services/applications, especilly for those running with kubernetes cluster;
    4. Integrate project ntopng(https://github.com/ntop) to enhance network traffic monitoring and analysis;   
    5. Combine the Web UI of NetData, Cilium(Hubble), and ntopng for visualized observing and troubleshooting, and better support single-host or 
       distributed scenario; 
    6. Use FastAPI(https://github.com/tiangolo/fastapi) to build the unified APIs for the whole system;
    7. A well-designed modular and plugin based software architecure together with preserved module interface for AI-assisted system management and 
       fault-tolerance, real-time data processing engine, and user defined functions.
    ...
