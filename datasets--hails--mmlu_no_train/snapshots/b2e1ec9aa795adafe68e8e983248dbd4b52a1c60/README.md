---
language:
- en
license: mit
task_categories:
- question-answering
pretty_name: MMLU loader with no auxiliary train set
dataset_info:
- config_name: abstract_algebra
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 21316
    num_examples: 100
  - name: validation
    num_bytes: 2232
    num_examples: 11
  - name: dev
    num_bytes: 918
    num_examples: 5
  download_size: 17170
  dataset_size: 24466
- config_name: all
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 6967453
    num_examples: 14042
  - name: validation
    num_bytes: 763484
    num_examples: 1531
  - name: dev
    num_bytes: 125353
    num_examples: 285
  download_size: 3987384
  dataset_size: 7856290
- config_name: anatomy
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 34594
    num_examples: 135
  - name: validation
    num_bytes: 3282
    num_examples: 14
  - name: dev
    num_bytes: 1010
    num_examples: 5
  download_size: 28891
  dataset_size: 38886
- config_name: astronomy
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 48735
    num_examples: 152
  - name: validation
    num_bytes: 5223
    num_examples: 16
  - name: dev
    num_bytes: 2129
    num_examples: 5
  download_size: 39343
  dataset_size: 56087
- config_name: business_ethics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 35140
    num_examples: 100
  - name: validation
    num_bytes: 3235
    num_examples: 11
  - name: dev
    num_bytes: 2273
    num_examples: 5
  download_size: 31646
  dataset_size: 40648
- config_name: clinical_knowledge
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 68572
    num_examples: 265
  - name: validation
    num_bytes: 7290
    num_examples: 29
  - name: dev
    num_bytes: 1308
    num_examples: 5
  download_size: 51682
  dataset_size: 77170
- config_name: college_biology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 51521
    num_examples: 144
  - name: validation
    num_bytes: 5111
    num_examples: 16
  - name: dev
    num_bytes: 1615
    num_examples: 5
  download_size: 43044
  dataset_size: 58247
- config_name: college_chemistry
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 26796
    num_examples: 100
  - name: validation
    num_bytes: 2484
    num_examples: 8
  - name: dev
    num_bytes: 1424
    num_examples: 5
  download_size: 26808
  dataset_size: 30704
- config_name: college_computer_science
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 45429
    num_examples: 100
  - name: validation
    num_bytes: 4959
    num_examples: 11
  - name: dev
    num_bytes: 2893
    num_examples: 5
  download_size: 41159
  dataset_size: 53281
- config_name: college_mathematics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 26999
    num_examples: 100
  - name: validation
    num_bytes: 2909
    num_examples: 11
  - name: dev
    num_bytes: 1596
    num_examples: 5
  download_size: 26806
  dataset_size: 31504
- config_name: college_medicine
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 85845
    num_examples: 173
  - name: validation
    num_bytes: 8337
    num_examples: 22
  - name: dev
    num_bytes: 1758
    num_examples: 5
  download_size: 56330
  dataset_size: 95940
- config_name: college_physics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 32107
    num_examples: 102
  - name: validation
    num_bytes: 3687
    num_examples: 11
  - name: dev
    num_bytes: 1495
    num_examples: 5
  download_size: 29566
  dataset_size: 37289
- config_name: computer_security
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 29212
    num_examples: 100
  - name: validation
    num_bytes: 4768
    num_examples: 11
  - name: dev
    num_bytes: 1194
    num_examples: 5
  download_size: 30177
  dataset_size: 35174
- config_name: conceptual_physics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 45867
    num_examples: 235
  - name: validation
    num_bytes: 5034
    num_examples: 26
  - name: dev
    num_bytes: 1032
    num_examples: 5
  download_size: 34995
  dataset_size: 51933
- config_name: econometrics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 48359
    num_examples: 114
  - name: validation
    num_bytes: 5147
    num_examples: 12
  - name: dev
    num_bytes: 1712
    num_examples: 5
  download_size: 36067
  dataset_size: 55218
- config_name: electrical_engineering
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 28900
    num_examples: 145
  - name: validation
    num_bytes: 3307
    num_examples: 16
  - name: dev
    num_bytes: 1090
    num_examples: 5
  download_size: 26773
  dataset_size: 33297
- config_name: elementary_mathematics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 79924
    num_examples: 378
  - name: validation
    num_bytes: 10042
    num_examples: 41
  - name: dev
    num_bytes: 1558
    num_examples: 5
  download_size: 55014
  dataset_size: 91524
- config_name: formal_logic
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 51789
    num_examples: 126
  - name: validation
    num_bytes: 6464
    num_examples: 14
  - name: dev
    num_bytes: 1825
    num_examples: 5
  download_size: 32911
  dataset_size: 60078
- config_name: global_facts
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 19991
    num_examples: 100
  - name: validation
    num_bytes: 2013
    num_examples: 10
  - name: dev
    num_bytes: 1297
    num_examples: 5
  download_size: 19285
  dataset_size: 23301
- config_name: high_school_biology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 116850
    num_examples: 310
  - name: validation
    num_bytes: 11746
    num_examples: 32
  - name: dev
    num_bytes: 1776
    num_examples: 5
  download_size: 78243
  dataset_size: 130372
- config_name: high_school_chemistry
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 63527
    num_examples: 203
  - name: validation
    num_bytes: 7630
    num_examples: 22
  - name: dev
    num_bytes: 1333
    num_examples: 5
  download_size: 45826
  dataset_size: 72490
- config_name: high_school_computer_science
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 47664
    num_examples: 100
  - name: validation
    num_bytes: 3619
    num_examples: 9
  - name: dev
    num_bytes: 3066
    num_examples: 5
  download_size: 39099
  dataset_size: 54349
- config_name: high_school_european_history
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 275568
    num_examples: 165
  - name: validation
    num_bytes: 30196
    num_examples: 18
  - name: dev
    num_bytes: 11712
    num_examples: 5
  download_size: 196297
  dataset_size: 317476
- config_name: high_school_geography
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 46972
    num_examples: 198
  - name: validation
    num_bytes: 4870
    num_examples: 22
  - name: dev
    num_bytes: 1516
    num_examples: 5
  download_size: 38282
  dataset_size: 53358
- config_name: high_school_government_and_politics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 73589
    num_examples: 193
  - name: validation
    num_bytes: 7870
    num_examples: 21
  - name: dev
    num_bytes: 1962
    num_examples: 5
  download_size: 52990
  dataset_size: 83421
- config_name: high_school_macroeconomics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 129375
    num_examples: 390
  - name: validation
    num_bytes: 14298
    num_examples: 43
  - name: dev
    num_bytes: 1466
    num_examples: 5
  download_size: 68785
  dataset_size: 145139
- config_name: high_school_mathematics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 62132
    num_examples: 270
  - name: validation
    num_bytes: 6536
    num_examples: 29
  - name: dev
    num_bytes: 1420
    num_examples: 5
  download_size: 45237
  dataset_size: 70088
- config_name: high_school_microeconomics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 82831
    num_examples: 238
  - name: validation
    num_bytes: 8321
    num_examples: 26
  - name: dev
    num_bytes: 1436
    num_examples: 5
  download_size: 49912
  dataset_size: 92588
- config_name: high_school_physics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 62999
    num_examples: 151
  - name: validation
    num_bytes: 7150
    num_examples: 17
  - name: dev
    num_bytes: 1592
    num_examples: 5
  download_size: 45510
  dataset_size: 71741
- config_name: high_school_psychology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 173565
    num_examples: 545
  - name: validation
    num_bytes: 18817
    num_examples: 60
  - name: dev
    num_bytes: 2023
    num_examples: 5
  download_size: 113185
  dataset_size: 194405
- config_name: high_school_statistics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 116306
    num_examples: 216
  - name: validation
    num_bytes: 10583
    num_examples: 23
  - name: dev
    num_bytes: 2646
    num_examples: 5
  download_size: 74951
  dataset_size: 129535
- config_name: high_school_us_history
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 302026
    num_examples: 204
  - name: validation
    num_bytes: 32266
    num_examples: 22
  - name: dev
    num_bytes: 8982
    num_examples: 5
  download_size: 200070
  dataset_size: 343274
- config_name: high_school_world_history
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 385478
    num_examples: 237
  - name: validation
    num_bytes: 46243
    num_examples: 26
  - name: dev
    num_bytes: 5015
    num_examples: 5
  download_size: 250329
  dataset_size: 436736
- config_name: human_aging
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 49431
    num_examples: 223
  - name: validation
    num_bytes: 5040
    num_examples: 23
  - name: dev
    num_bytes: 1071
    num_examples: 5
  download_size: 41223
  dataset_size: 55542
- config_name: human_sexuality
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 34587
    num_examples: 131
  - name: validation
    num_bytes: 2637
    num_examples: 12
  - name: dev
    num_bytes: 1160
    num_examples: 5
  download_size: 32560
  dataset_size: 38384
- config_name: international_law
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 56060
    num_examples: 121
  - name: validation
    num_bytes: 6734
    num_examples: 13
  - name: dev
    num_bytes: 2511
    num_examples: 5
  download_size: 41619
  dataset_size: 65305
- config_name: jurisprudence
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 35810
    num_examples: 108
  - name: validation
    num_bytes: 3904
    num_examples: 11
  - name: dev
    num_bytes: 1376
    num_examples: 5
  download_size: 33605
  dataset_size: 41090
- config_name: logical_fallacies
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 53528
    num_examples: 163
  - name: validation
    num_bytes: 5469
    num_examples: 18
  - name: dev
    num_bytes: 1666
    num_examples: 5
  download_size: 33696
  dataset_size: 60663
- config_name: machine_learning
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 36108
    num_examples: 112
  - name: validation
    num_bytes: 3440
    num_examples: 11
  - name: dev
    num_bytes: 2411
    num_examples: 5
  download_size: 31148
  dataset_size: 41959
- config_name: management
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 21432
    num_examples: 103
  - name: validation
    num_bytes: 1962
    num_examples: 11
  - name: dev
    num_bytes: 956
    num_examples: 5
  download_size: 22855
  dataset_size: 24350
- config_name: marketing
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 66055
    num_examples: 234
  - name: validation
    num_bytes: 7707
    num_examples: 25
  - name: dev
    num_bytes: 1534
    num_examples: 5
  download_size: 49774
  dataset_size: 75296
- config_name: medical_genetics
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 22852
    num_examples: 100
  - name: validation
    num_bytes: 3213
    num_examples: 11
  - name: dev
    num_bytes: 1177
    num_examples: 5
  download_size: 25802
  dataset_size: 27242
- config_name: miscellaneous
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 161003
    num_examples: 783
  - name: validation
    num_bytes: 15780
    num_examples: 86
  - name: dev
    num_bytes: 772
    num_examples: 5
  download_size: 115124
  dataset_size: 177555
- config_name: moral_disputes
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 114034
    num_examples: 346
  - name: validation
    num_bytes: 13092
    num_examples: 38
  - name: dev
    num_bytes: 1833
    num_examples: 5
  download_size: 76070
  dataset_size: 128959
- config_name: moral_scenarios
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 391019
    num_examples: 895
  - name: validation
    num_bytes: 44226
    num_examples: 100
  - name: dev
    num_bytes: 2141
    num_examples: 5
  download_size: 109896
  dataset_size: 437386
- config_name: nutrition
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 96376
    num_examples: 306
  - name: validation
    num_bytes: 8853
    num_examples: 33
  - name: dev
    num_bytes: 2138
    num_examples: 5
  download_size: 69077
  dataset_size: 107367
- config_name: philosophy
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 84415
    num_examples: 311
  - name: validation
    num_bytes: 9648
    num_examples: 34
  - name: dev
    num_bytes: 1046
    num_examples: 5
  download_size: 61939
  dataset_size: 95109
- config_name: prehistory
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 94118
    num_examples: 324
  - name: validation
    num_bytes: 10763
    num_examples: 35
  - name: dev
    num_bytes: 1936
    num_examples: 5
  download_size: 68853
  dataset_size: 106817
- config_name: professional_accounting
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 132152
    num_examples: 282
  - name: validation
    num_bytes: 15197
    num_examples: 31
  - name: dev
    num_bytes: 2271
    num_examples: 5
  download_size: 87324
  dataset_size: 149620
- config_name: professional_law
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 1922430
    num_examples: 1534
  - name: validation
    num_bytes: 206907
    num_examples: 170
  - name: dev
    num_bytes: 6698
    num_examples: 5
  download_size: 1167861
  dataset_size: 2136035
- config_name: professional_medicine
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 224349
    num_examples: 272
  - name: validation
    num_bytes: 24610
    num_examples: 31
  - name: dev
    num_bytes: 3920
    num_examples: 5
  download_size: 153269
  dataset_size: 252879
- config_name: professional_psychology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 242411
    num_examples: 612
  - name: validation
    num_bytes: 30952
    num_examples: 69
  - name: dev
    num_bytes: 2390
    num_examples: 5
  download_size: 159384
  dataset_size: 275753
- config_name: public_relations
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 30948
    num_examples: 110
  - name: validation
    num_bytes: 4794
    num_examples: 12
  - name: dev
    num_bytes: 1584
    num_examples: 5
  download_size: 31527
  dataset_size: 37326
- config_name: security_studies
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 209732
    num_examples: 245
  - name: validation
    num_bytes: 23165
    num_examples: 27
  - name: dev
    num_bytes: 5423
    num_examples: 5
  download_size: 140285
  dataset_size: 238320
- config_name: sociology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 68844
    num_examples: 201
  - name: validation
    num_bytes: 7458
    num_examples: 22
  - name: dev
    num_bytes: 1666
    num_examples: 5
  download_size: 56507
  dataset_size: 77968
- config_name: us_foreign_policy
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 30531
    num_examples: 100
  - name: validation
    num_bytes: 3483
    num_examples: 11
  - name: dev
    num_bytes: 1704
    num_examples: 5
  download_size: 29054
  dataset_size: 35718
- config_name: virology
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 40739
    num_examples: 166
  - name: validation
    num_bytes: 5667
    num_examples: 18
  - name: dev
    num_bytes: 1144
    num_examples: 5
  download_size: 38256
  dataset_size: 47550
- config_name: world_religions
  features:
  - name: question
    dtype: string
  - name: subject
    dtype: string
  - name: choices
    sequence: string
  - name: answer
    dtype:
      class_label:
        names:
          '0': A
          '1': B
          '2': C
          '3': D
  splits:
  - name: test
    num_bytes: 28511
    num_examples: 171
  - name: validation
    num_bytes: 3114
    num_examples: 19
  - name: dev
    num_bytes: 753
    num_examples: 5
  download_size: 27192
  dataset_size: 32378
configs:
- config_name: abstract_algebra
  data_files:
  - split: test
    path: abstract_algebra/test-*
  - split: validation
    path: abstract_algebra/validation-*
  - split: dev
    path: abstract_algebra/dev-*
- config_name: all
  data_files:
  - split: test
    path: all/test-*
  - split: validation
    path: all/validation-*
  - split: dev
    path: all/dev-*
- config_name: anatomy
  data_files:
  - split: test
    path: anatomy/test-*
  - split: validation
    path: anatomy/validation-*
  - split: dev
    path: anatomy/dev-*
- config_name: astronomy
  data_files:
  - split: test
    path: astronomy/test-*
  - split: validation
    path: astronomy/validation-*
  - split: dev
    path: astronomy/dev-*
- config_name: business_ethics
  data_files:
  - split: test
    path: business_ethics/test-*
  - split: validation
    path: business_ethics/validation-*
  - split: dev
    path: business_ethics/dev-*
- config_name: clinical_knowledge
  data_files:
  - split: test
    path: clinical_knowledge/test-*
  - split: validation
    path: clinical_knowledge/validation-*
  - split: dev
    path: clinical_knowledge/dev-*
- config_name: college_biology
  data_files:
  - split: test
    path: college_biology/test-*
  - split: validation
    path: college_biology/validation-*
  - split: dev
    path: college_biology/dev-*
- config_name: college_chemistry
  data_files:
  - split: test
    path: college_chemistry/test-*
  - split: validation
    path: college_chemistry/validation-*
  - split: dev
    path: college_chemistry/dev-*
- config_name: college_computer_science
  data_files:
  - split: test
    path: college_computer_science/test-*
  - split: validation
    path: college_computer_science/validation-*
  - split: dev
    path: college_computer_science/dev-*
- config_name: college_mathematics
  data_files:
  - split: test
    path: college_mathematics/test-*
  - split: validation
    path: college_mathematics/validation-*
  - split: dev
    path: college_mathematics/dev-*
- config_name: college_medicine
  data_files:
  - split: test
    path: college_medicine/test-*
  - split: validation
    path: college_medicine/validation-*
  - split: dev
    path: college_medicine/dev-*
- config_name: college_physics
  data_files:
  - split: test
    path: college_physics/test-*
  - split: validation
    path: college_physics/validation-*
  - split: dev
    path: college_physics/dev-*
- config_name: computer_security
  data_files:
  - split: test
    path: computer_security/test-*
  - split: validation
    path: computer_security/validation-*
  - split: dev
    path: computer_security/dev-*
- config_name: conceptual_physics
  data_files:
  - split: test
    path: conceptual_physics/test-*
  - split: validation
    path: conceptual_physics/validation-*
  - split: dev
    path: conceptual_physics/dev-*
- config_name: econometrics
  data_files:
  - split: test
    path: econometrics/test-*
  - split: validation
    path: econometrics/validation-*
  - split: dev
    path: econometrics/dev-*
- config_name: electrical_engineering
  data_files:
  - split: test
    path: electrical_engineering/test-*
  - split: validation
    path: electrical_engineering/validation-*
  - split: dev
    path: electrical_engineering/dev-*
- config_name: elementary_mathematics
  data_files:
  - split: test
    path: elementary_mathematics/test-*
  - split: validation
    path: elementary_mathematics/validation-*
  - split: dev
    path: elementary_mathematics/dev-*
- config_name: formal_logic
  data_files:
  - split: test
    path: formal_logic/test-*
  - split: validation
    path: formal_logic/validation-*
  - split: dev
    path: formal_logic/dev-*
- config_name: global_facts
  data_files:
  - split: test
    path: global_facts/test-*
  - split: validation
    path: global_facts/validation-*
  - split: dev
    path: global_facts/dev-*
- config_name: high_school_biology
  data_files:
  - split: test
    path: high_school_biology/test-*
  - split: validation
    path: high_school_biology/validation-*
  - split: dev
    path: high_school_biology/dev-*
- config_name: high_school_chemistry
  data_files:
  - split: test
    path: high_school_chemistry/test-*
  - split: validation
    path: high_school_chemistry/validation-*
  - split: dev
    path: high_school_chemistry/dev-*
- config_name: high_school_computer_science
  data_files:
  - split: test
    path: high_school_computer_science/test-*
  - split: validation
    path: high_school_computer_science/validation-*
  - split: dev
    path: high_school_computer_science/dev-*
- config_name: high_school_european_history
  data_files:
  - split: test
    path: high_school_european_history/test-*
  - split: validation
    path: high_school_european_history/validation-*
  - split: dev
    path: high_school_european_history/dev-*
- config_name: high_school_geography
  data_files:
  - split: test
    path: high_school_geography/test-*
  - split: validation
    path: high_school_geography/validation-*
  - split: dev
    path: high_school_geography/dev-*
- config_name: high_school_government_and_politics
  data_files:
  - split: test
    path: high_school_government_and_politics/test-*
  - split: validation
    path: high_school_government_and_politics/validation-*
  - split: dev
    path: high_school_government_and_politics/dev-*
- config_name: high_school_macroeconomics
  data_files:
  - split: test
    path: high_school_macroeconomics/test-*
  - split: validation
    path: high_school_macroeconomics/validation-*
  - split: dev
    path: high_school_macroeconomics/dev-*
- config_name: high_school_mathematics
  data_files:
  - split: test
    path: high_school_mathematics/test-*
  - split: validation
    path: high_school_mathematics/validation-*
  - split: dev
    path: high_school_mathematics/dev-*
- config_name: high_school_microeconomics
  data_files:
  - split: test
    path: high_school_microeconomics/test-*
  - split: validation
    path: high_school_microeconomics/validation-*
  - split: dev
    path: high_school_microeconomics/dev-*
- config_name: high_school_physics
  data_files:
  - split: test
    path: high_school_physics/test-*
  - split: validation
    path: high_school_physics/validation-*
  - split: dev
    path: high_school_physics/dev-*
- config_name: high_school_psychology
  data_files:
  - split: test
    path: high_school_psychology/test-*
  - split: validation
    path: high_school_psychology/validation-*
  - split: dev
    path: high_school_psychology/dev-*
- config_name: high_school_statistics
  data_files:
  - split: test
    path: high_school_statistics/test-*
  - split: validation
    path: high_school_statistics/validation-*
  - split: dev
    path: high_school_statistics/dev-*
- config_name: high_school_us_history
  data_files:
  - split: test
    path: high_school_us_history/test-*
  - split: validation
    path: high_school_us_history/validation-*
  - split: dev
    path: high_school_us_history/dev-*
- config_name: high_school_world_history
  data_files:
  - split: test
    path: high_school_world_history/test-*
  - split: validation
    path: high_school_world_history/validation-*
  - split: dev
    path: high_school_world_history/dev-*
- config_name: human_aging
  data_files:
  - split: test
    path: human_aging/test-*
  - split: validation
    path: human_aging/validation-*
  - split: dev
    path: human_aging/dev-*
- config_name: human_sexuality
  data_files:
  - split: test
    path: human_sexuality/test-*
  - split: validation
    path: human_sexuality/validation-*
  - split: dev
    path: human_sexuality/dev-*
- config_name: international_law
  data_files:
  - split: test
    path: international_law/test-*
  - split: validation
    path: international_law/validation-*
  - split: dev
    path: international_law/dev-*
- config_name: jurisprudence
  data_files:
  - split: test
    path: jurisprudence/test-*
  - split: validation
    path: jurisprudence/validation-*
  - split: dev
    path: jurisprudence/dev-*
- config_name: logical_fallacies
  data_files:
  - split: test
    path: logical_fallacies/test-*
  - split: validation
    path: logical_fallacies/validation-*
  - split: dev
    path: logical_fallacies/dev-*
- config_name: machine_learning
  data_files:
  - split: test
    path: machine_learning/test-*
  - split: validation
    path: machine_learning/validation-*
  - split: dev
    path: machine_learning/dev-*
- config_name: management
  data_files:
  - split: test
    path: management/test-*
  - split: validation
    path: management/validation-*
  - split: dev
    path: management/dev-*
- config_name: marketing
  data_files:
  - split: test
    path: marketing/test-*
  - split: validation
    path: marketing/validation-*
  - split: dev
    path: marketing/dev-*
- config_name: medical_genetics
  data_files:
  - split: test
    path: medical_genetics/test-*
  - split: validation
    path: medical_genetics/validation-*
  - split: dev
    path: medical_genetics/dev-*
- config_name: miscellaneous
  data_files:
  - split: test
    path: miscellaneous/test-*
  - split: validation
    path: miscellaneous/validation-*
  - split: dev
    path: miscellaneous/dev-*
- config_name: moral_disputes
  data_files:
  - split: test
    path: moral_disputes/test-*
  - split: validation
    path: moral_disputes/validation-*
  - split: dev
    path: moral_disputes/dev-*
- config_name: moral_scenarios
  data_files:
  - split: test
    path: moral_scenarios/test-*
  - split: validation
    path: moral_scenarios/validation-*
  - split: dev
    path: moral_scenarios/dev-*
- config_name: nutrition
  data_files:
  - split: test
    path: nutrition/test-*
  - split: validation
    path: nutrition/validation-*
  - split: dev
    path: nutrition/dev-*
- config_name: philosophy
  data_files:
  - split: test
    path: philosophy/test-*
  - split: validation
    path: philosophy/validation-*
  - split: dev
    path: philosophy/dev-*
- config_name: prehistory
  data_files:
  - split: test
    path: prehistory/test-*
  - split: validation
    path: prehistory/validation-*
  - split: dev
    path: prehistory/dev-*
- config_name: professional_accounting
  data_files:
  - split: test
    path: professional_accounting/test-*
  - split: validation
    path: professional_accounting/validation-*
  - split: dev
    path: professional_accounting/dev-*
- config_name: professional_law
  data_files:
  - split: test
    path: professional_law/test-*
  - split: validation
    path: professional_law/validation-*
  - split: dev
    path: professional_law/dev-*
- config_name: professional_medicine
  data_files:
  - split: test
    path: professional_medicine/test-*
  - split: validation
    path: professional_medicine/validation-*
  - split: dev
    path: professional_medicine/dev-*
- config_name: professional_psychology
  data_files:
  - split: test
    path: professional_psychology/test-*
  - split: validation
    path: professional_psychology/validation-*
  - split: dev
    path: professional_psychology/dev-*
- config_name: public_relations
  data_files:
  - split: test
    path: public_relations/test-*
  - split: validation
    path: public_relations/validation-*
  - split: dev
    path: public_relations/dev-*
- config_name: security_studies
  data_files:
  - split: test
    path: security_studies/test-*
  - split: validation
    path: security_studies/validation-*
  - split: dev
    path: security_studies/dev-*
- config_name: sociology
  data_files:
  - split: test
    path: sociology/test-*
  - split: validation
    path: sociology/validation-*
  - split: dev
    path: sociology/dev-*
- config_name: us_foreign_policy
  data_files:
  - split: test
    path: us_foreign_policy/test-*
  - split: validation
    path: us_foreign_policy/validation-*
  - split: dev
    path: us_foreign_policy/dev-*
- config_name: virology
  data_files:
  - split: test
    path: virology/test-*
  - split: validation
    path: virology/validation-*
  - split: dev
    path: virology/dev-*
- config_name: world_religions
  data_files:
  - split: test
    path: world_religions/test-*
  - split: validation
    path: world_religions/validation-*
  - split: dev
    path: world_religions/dev-*
---
This dataset contains a copy of the `cais/mmlu` HF dataset but without the `auxiliary_train` split that takes a long time to generate again each time when loading multiple subsets of the dataset.

Please visit https://huggingface.co/datasets/cais/mmlu for more information on the MMLU dataset.