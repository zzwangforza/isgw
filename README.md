基于ACE的高性能服务端框架，单进程多线程，支持select/epoll等模型，同时支持tcp和udp协议，支持二进制(pb或自定义)和文本格式，开源，相对多进程模型的框架来说更易维护，更轻量。业务侧只需要开发自己的逻辑处理即可实现高效的业务服务器。已经在腾讯互娱(IEG)大部分平台类产品中成熟应用，比如idip，游戏人生，心悦，帮帮，新终端游戏中心aj，cross等，现在公司很多BG都有产品在逐渐使用。