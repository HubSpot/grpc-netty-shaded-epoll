# grpc-netty-shaded-epoll

When using grpc, you can use grpc-netty-shaded in order to avoid netty conflicts. Unfortunately, it doesn't work with epoll. This repo builds a shaded version of netty-transport-native-epoll with the packages relocated the same way that grpc-netty-shaded expects. 
