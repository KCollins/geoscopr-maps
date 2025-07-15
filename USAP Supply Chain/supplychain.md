We want to redraw a version of this image:
<img width="1348" height="1110" alt="image34783" src="https://github.com/user-attachments/assets/e1a91420-5c49-401d-85fb-9eb0ed7fbe48" />

From this document: https://nsf-gov-resources.nsf.gov/files/antarctica-07232012.pdf

Here's a flowchart in mermaid:
```mermaid
flowchart TB
    subgraph ide1 [Antarctica]
    McMurdo<-->FieldA["Field A"]
    McMurdo<-->SouthPole["South Pole"]
    FieldA<-->FieldC["Field C"]
    SouthPole<-->FieldB["Field B"]
    Palmer
    end
    subgraph ide2 [North America]
    Hueneme["Port Hueneme"]
    end
    subgraph ide3 [South America]
    Palmer<-->PuntaArenas["Punta Arenas"]
    PuntaArenas<-->Hueneme
    end
    subgraph ide4 [New Zealand]
    NZ["Christchurch/Port Lyttleton"]<-->McMurdo
    NZ<-->Hueneme
    end
```
