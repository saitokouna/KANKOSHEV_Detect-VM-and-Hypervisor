Type of detecthion Hypervisor or VM  
1)NtQuerySystemInformation with SystemHypervisorDetailInformation  
2)rdtsc(with cpuid & GetHeap)  
3)readmsr  
4)cpuid is Hyperv   
5)SetThreadContext with cpuid  
6)Compare cpuid list 
7)xgetbv with VM-exit