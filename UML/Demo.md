# 时序图


A->B:(通过userId,获取权限)
B->A:(返回权限值 p)
A->A:(校验权限是否为预期权限)
A->C:（获取该userId的 p 权限数据）
C->A:(返回数据)
A->A:(装配格式化)





Title: Here is a title
A->B: Normal line 
B-->C: Dashed line 
C->>D: Open arrow 
D-->>A: Dashed open arrow

Note left of A: Note to the\n left of A 
Note right of A: Note to the\n right of A 
Note over A: Note over A 
Note over C,D: Note over both C and D




sequenceDiagram
　　Alice->>Bob: Hello Bob, how are you?
　　alt is sick
　　　　Bob->>Alice:not so good :(
　　else is well
　　　　Bob->>Alice:good
　　end
　　opt Extra response
　　　　Bob->>Alice:Thanks for asking
　　end






