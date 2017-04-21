A Docker Compose example for containers with [Intel SGX] support (https://software.intel.com/en-us/sgx) [SDK and
PSW](https://github.com/01org/linux-sgx) (platform software, i.e., runtime).

Intel SGX [kernel module](https://github.com/01org/linux-sgx-driver) has to be loaded on the
host and you have to provide it to the container when you run it:

```
docker-compose up
```

SDK is installed under `/opt/intel/sgxsdk`. You should do:
