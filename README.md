# TabComp

This repo belongs to the Paper- <u>TabComp: Visual Table Reading Comprehension.</u> <br>
Repo contains dataset TabComp, whose structure is as follows:-
```
TabComp
├── **Instruction-Tuning-Format**
│   ├── **images**
│   │   ├── **test**
│   │   │   └── image1, image2, image3. . . imageN
│   │   └── train
│   │       └── image1, image2, image3. . . imageN
│   │
│   └── **json**
│       ├── **test**
│       │   └── test.jsonl
│       └── **train**
│           └── train.jsonl
│
└── **Question-Answering-Format**
    ├── **train**
    │   ├── **documents**
    │   │   └── image1, image2, image3. . . imageN
    │   └── metadata.jsonl
    │
    └── **test**
        ├── **documents**
        │   └── image1, image2, image3. . . imageN
        └── metadata.jsonl
```
