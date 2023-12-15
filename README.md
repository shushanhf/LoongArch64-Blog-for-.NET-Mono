# LoongArch64-Blog-for-.NET-Mono
Record or  publish the progress schedule for porting the .NET/Mono on LoongArch64 platform.

## .NET8-Loongarch64  
See sdk-8.0-LA_upstream_newABI/README.txt  

## .NET6-Loongarch64-Porting
-------------2022.11.10  
* SDK6.0-LoongArch64 had been published here,  [Download](http://www.loongnix.cn/zh/api/dotnet/)


## Mono6.13-LoongArch64-Porting
* had finished a initial version for LoongArch64-Mono.
Finished the the backend and had compiled sucessfully on LoongArch64-linux.
<pre>
qiao@3a5000-213:~/work_qiao/la_mono/mono/mini$ ./mono --version
Mono JIT compiler version 6.13.0 (loongarch64-dev-6.0/11ce995f841 2021年 11月 02日 星期二 07:54:19 UTC)
Copyright (C) Novell, Inc, Xamarin Inc and Contributors. www.mono-project.com
	TLS:           __thread
	SIGSEGV:       normal
	Notifications: epoll
	Architecture:  loongarch64
	Disabled:      none
	Misc:          softdebug 
	Interpreter:   yes
	Suspend:       preemptive
	GC:            sgen (concurrent by default)
</pre>
* [Download](http://www.loongnix.cn/zh/api/dotnet/)
