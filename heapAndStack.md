### swift 의 heap 영역과 stack 영역에관하여

```
stack 메모리 영역과 heap 메모리 영역에 저장되는 기준은
value sementics 인지 혹은 reference sementics 인지에 따라 결졍된다.

struct 나 enum 등 값 타입은 stack 영역에 저장된다. 
따라서 reference counting 도 필요없다.

하지만 class 와같은 참조 타입은 heap 영역에 저장되기 때문에
reference counting 이 증가한다.
```

알고있는 사실이었지만 면접때 긴장해서 대답을 제대로 못했다.  
다시한번 복습...
