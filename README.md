# userStudy

This repository is part of the BlocklyCyberRange projekt in which we investigate the applicability of the Visual Programming Language [Blockly](https://developers.google.com/blockly) for Cyber Range Training and contains the data and results of a user study in form of a Randomized Controlled Trial (RCT).

## File description:
 - [questions_evaluation.xlsx](https://github.com/BlocklyCyberRange/userStudy/blob/main/questions_evaluation.xlsx) : The surveys and statement catalogues we used for assessing the particpants' learning outcome and subjective learning experience
 - [trainee_dataset.xlsx](https://github.com/BlocklyCyberRange/userStudy/blob/main/trainee_dataset.xlsx): the anonymized raw data that was collected in the user study
 - [trainee_dataset.csv](https://github.com/BlocklyCyberRange/userStudy/blob/main/trainee_dataset.csv): the data set in csv format
 - [spss_output.spv](https://github.com/BlocklyCyberRange/userStudy/blob/main/spss_output.spv): the results of the statistical analyses conducted in SPSS
 - [spss_output.pdf](https://github.com/BlocklyCyberRange/userStudy/blob/main/spss_output.pdf): the core results of the statisical analyses in pdf format
 - [data_analysis.ipynb](https://github.com/BlocklyCyberRange/userStudy/blob/main/data_analysis.ipynb): Jupyter-Notebook showcasing some initial Data Analysis steps.

## Columns of data set

| Column          | Type               | Range               | Description                                                                                               |
|-----------------|--------------------|---------------------|-----------------------------------------------------------------------------------------------------------|
| group           | string             | {"Json"; "Blockly"} | Group assignment for the Random Controlled Test                                                           |
| start_time      | ISO 8601 timestamp |                     | Timestamp when trainee started cyber range                                                                |
| total_time      | in64               |                     | Time difference between task5_end and start_time in seconds                                               |
| task1_start     | ISO 8601 timestamp |                     | Timestamp when trainee started Task 1                                                                     |
| task1_end       | ISO 8601 timestamp |                     | Timestamp when trainee ended Task 1                                                                       |
| task1_time_diff | int64              |                     | Time difference between task1_end and task1_start  in seconds                                             |
| task1_tlx_1     | int64              | {1;2;3;4;5}         | How mentally demanding was task1?                                                                         |
| task1_tlx_2     | int64              | {1;2;3;4;5}         | How hurried or rushed was the pace of task1?                                                              |
| task1_tlx_3     | int64              | {1;2;3;4;5}         | How successful were you in accomplishing what you were asked to do in   task1?                            |
| task1_tlx_4     | int64              | {1;2;3;4;5}         | How insecure, discouraged, irritated, stressed, or annoyed were you   during task1?                       |
| task1_tlx_avg   | float64            | [1;5]               | Average from task1_tlx_1, task1_tlx_2, task1_tlx_3, task1_tlx_4                                           |
| task2_start     | ISO 8601 timestamp |                     | Timestamp when trainee started Task 2                                                                     |
| task2_end       | ISO 8601 timestamp |                     | Timestamp when trainee ended Task 2                                                                       |
| task2_time_diff | int64              |                     | Time difference between task2_end and task2_start  in seconds                                             |
| task2_tlx_1     | int64              | {1;2;3;4;5}         | How mentally demanding was task2?                                                                         |
| task2_tlx_2     | int64              | {1;2;3;4;5}         | How hurried or rushed was the pace of task2?                                                              |
| task2_tlx_3     | int64              | {1;2;3;4;5}         | How successful were you in accomplishing what you were asked to do in   task2?                            |
| task2_tlx_4     | int64              | {1;2;3;4;5}         | How insecure, discouraged, irritated, stressed, or annoyed were you   during task2?                       |
| task2_tlx_avg   | float64            | [1;5]               | Average from task2_tlx_1, task2_tlx_2, task2_tlx_3, task2_tlx_4                                           |
| task3_start     | ISO 8601 timestamp |                     | Timestamp when trainee started Task 3                                                                     |
| task3_end       | ISO 8601 timestamp |                     | Timestamp when trainee ended Task 3                                                                       |
| task3_time_diff | int64              |                     | Time difference between task3_end and task3_start  in seconds                                             |
| task3_tlx_1     | int64              | {1;2;3;4;5}         | How mentally demanding was task3?                                                                         |
| task3_tlx_2     | int64              | {1;2;3;4;5}         | How hurried or rushed was the pace of task3?                                                              |
| task3_tlx_3     | int64              | {1;2;3;4;5}         | How successful were you in accomplishing what you were asked to do in   task3?                            |
| task3_tlx_4     | int64              | {1;2;3;4;5}         | How insecure, discouraged, irritated, stressed, or annoyed were you   during task3?                       |
| task3_tlx_avg   | float64            | [1;5]               | Average from task3_tlx_1, task3_tlx_2, task3_tlx_3, task3_tlx_4                                           |
| task4_start     | ISO 8601 timestamp |                     | Timestamp when trainee started Task 4                                                                     |
| task4_end       | ISO 8601 timestamp |                     | Timestamp when trainee ended Task 4                                                                       |
| task4_time_diff | int64              |                     | Time difference between task4_end and task4_start in seconds                                              |
| task4_tlx_1     | int64              | {1;2;3;4;5}         | How mentally demanding was task4?                                                                         |
| task4_tlx_2     | int64              | {1;2;3;4;5}         | How hurried or rushed was the pace of task4?                                                              |
| task4_tlx_3     | int64              | {1;2;3;4;5}         | How successful were you in accomplishing what you were asked   to do in task4?                            |
| task4_tlx_4     | int64              | {1;2;3;4;5}         | How insecure, discouraged, irritated, stressed, or annoyed were you   during task4?                       |
| task4_tlx_avg   | float64            | [1;5]               | Average from task4_tlx_1, task4_tlx_2, task4_tlx_3, task4_tlx_4                                           |
| task5_start     | ISO 8601 timestamp |                     | Timestamp when trainee started Task 5                                                                     |
| task5_end       | ISO 8601 timestamp |                     | Timestamp when trainee ended Task 5                                                                       |
| task5_time_diff | int64              |                     | Time difference between task5_end and task5_start  in seconds                                             |
| task5_tlx_1     | int64              | {1;2;3;4;5}         | How mentally demanding was task5?                                                                         |
| task5_tlx_2     | int64              | {1;2;3;4;5}         | How hurried or rushed was the pace of task5?                                                              |
| task5_tlx_3     | int64              | {1;2;3;4;5}         | How successful were you in accomplishing what you were asked to do in   task5?                            |
| task5_tlx_4     | int64              | {1;2;3;4;5}         | How insecure, discouraged, irritated, stressed, or annoyed were you   during task5?                       |
| task5_tlx_avg   | float64            | [1;5]               | Average from task5_tlx_1, task5_tlx_2, task5_tlx_3, task5_tlx_4                                           |
| pre_nsk_1       | int64              | {0;1}               | What is the ARP protocol?                                                                                 |
| pre_nsk_2       | int64              | {0;1}               | What is a PLC (SPS)?                                                                                      |
| pre_nsk_3       | int64              | {0;1}               | What is an ICS?                                                                                           |
| pre_nsk_avg     | float64            | [0;1]               | Average from pre_nsk_1, pre_nsk_2, pre_nsk_3                                                              |
| pre_siemk_1     | int64              | {0;1}               | What is the purpose of a SIEM system?                                                                     |
| pre_siemk_2     | int64              | {0;1}               | What is a SIEM event?                                                                                     |
| pre_siemk_3     | int64              | {0;1}               | What is the difference between an alarm and an event                                                      |
| pre_siemk_avg   | float64            | [0;1]               | Average from pre_siemk_1, pre_siemk_2, pre_siemk_3                                                        |
| pre_atkk_1      | int64              | {0;1}               | What is a Man In The Middle (MiTM) Attack?                                                                |
| pre_atkk_2      | int64              | {0;1}               | Effect of a MitM Attack on an industrial system?                                                          |
| pre_atkk_3      | int64              | {0;1}               | How does ARP spoofing work?                                                                               |
| pre_atkk_avg    | float64            | [0;1]               | Average from pre_attk_1, pre_attk_2, pre_atkk_3                                                           |
| pre_siemdk_1    | int64              | {0;1}               | What does occurence define in a SIEM rule?                                                                |
| pre_siemdk_2    | int64              | {0;1}               | What does timeout define in a SIEM rule?                                                                  |
| pre_siemdk_3    | int64              | {0;1}               | What is a stage within a SIEM directive?                                                                  |
| pre_siemd_avg   | float64            | [0;1]               | Average from pre_siemdk_1, pre_siemdk_2, pre_siemdk_3                                                     |
| post_nsk_1      | int64              | {0;1}               | What is the ARP protocol?                                                                                 |
| post_nsk_2      | int64              | {0;1}               | What is a PLC (SPS)?                                                                                      |
| post_nsk_3      | int64              | {0;1}               | What is an ICS?                                                                                           |
| post_nsk_avg    | float64            | [0;1]               | Average from post_nsk_1, post_nsk_2, post_nsk_3                                                           |
| post_siemk_1    | int64              | {0;1}               | What is the purpose of a SIEM system?                                                                     |
| post_siemk_2    | int64              | {0;1}               | What is a SIEM event?                                                                                     |
| post_siemk_3    | int64              | {0;1}               | What is the difference between an alarm and an event                                                      |
| post_siemk_avg  | float64            | [0;1]               | Average from post_siemk_1, post_siemk_2, post_siemk_3                                                     |
| post_atkk_1     | int64              | {0;1}               | What is a Man In The Middle (MiTM) Attack?                                                                |
| post_atkk_2     | int64              | {0;1}               | Effect of a MitM Attack on an industrial system?                                                          |
| post_atkk_3     | int64              | {0;1}               | How does ARP spoofing work?                                                                               |
| pst_atkk_avg    | float64            | [0;1]               | Average from post_attk_1, post_attk_2, post_atkk_3                                                        |
| post_siemdk_1   | int64              | {0;1}               | What does occurence define in a SIEM rule?                                                                |
| post_siemdk_2   | int64              | {0;1}               | What does timeout define in a SIEM rule?                                                                  |
| post_siemdk_3   | int64              | {0;1}               | What is a stage within a SIEM directive?                                                                  |
| post_siemdk_avg | float64            | [0;1]               | Average from post_siemdk_1, post_siemdk_2, post_siemdk_3                                                  |
| pre_all_avg     | float64            | [0;1]               | Average from pre_nsk_avg, pre_siemk_avg, pre_attk_avg, pre_siemdk_avg                                     |
| post_all_avg    | float64            | [0;1]               | Average from post_nsk_avg, post_siemk_avg, post_attk_avg, post_siemdk_avg                                 |
| diff_siemk_1    | int64              | {-1;0;1}            | Is post_siemk_1 better/same/worse than pre_siemk_1?                                                       |
| diff_siemk_2    | int64              | {-1;0;1}            | Is post_siemk_2 better/same/worse than pre_siemk_2?                                                       |
| diff_siemk_3    | int64              | {-1;0;1}            | Is post_siemk_3 better/same/worse than pre_siemk_3?                                                       |
| diff_siemk_avg  | float64            | [-1;1]              | Is post_siemk_avg better/same/worse than pre_siemk_avg?                                                   |
| diff_atkk_1     | int64              | {-1;0;1}            | Is post_attk_1 better/same/worse than pre_attk_1?                                                         |
| diff_atkk_2     | int64              | {-1;0;1}            | Is post_attk_2 better/same/worse than pre_attk_2?                                                         |
| diff_atkk_3     | int64              | {-1;0;1}            | Is post_attk_3 better/same/worse than pre_attk_3?                                                         |
| diff_atkk_avg   | float64            | [-1;1]              | Is post_attk_avg better/same/worse than pre_attk_avg?                                                     |
| diff_siemdk_1   | int64              | {-1;0;1}            | Is post_siemdk_1 better/same/worse than pre_siemdk_1?                                                     |
| diff_siemdk_2   | int64              | {-1;0;1}            | Is post_siemdk_2 better/same/worse than pre_siemdk_2?                                                     |
| diff_siemdk_3   | int64              | {-1;0;1}            | Is post_siemdk_3 better/same/worse than pre_siemdk_3?                                                     |
| diff_siemdk_avg | float64            | [-1;1]              | Is post_siemdk_avg better/same/worse than pre_siemdk_avg?                                                 |
| diff_all_avg    | float64            | [-1;1]              | Is post_all_avg better/same/worse than pre_all_avg?                                                       |
| post_A1         | int64              | {1;2;3;4;5}         | The scenario and context of the training were interesting.                                                |
| post_A2         | int64              | {1;2;3;4;5}         | I wanted to successfully finish the training and complete all the tasks.                                  |
| post_RV1        | int64              | {1;2;3;4;5}         | To me, the scenario and context seemed to be realistic.                                                   |
| post_RV2        | int64              | {1;2;3;4;5}         | In my opinion, the tasks I performed represent skills that are required   in real incident repsonse work. |
| post_C1         | int64              | {1;2;3;4;5}         | During the training, I felt I was in control over my actions.                                             |
| post_C2         | int64              | {1;2;3;4;5}         | During the training, I had a sense that I made good progress.                                             |
| post_S1         | int64              | {1;2;3;4;5}         | During the training, I experienced excitement.                                                            |
| post_S2         | int64              | {1;2;3;4;5}         | I was satisfied with my performance during the training.                                                  |
| post_A_avg      | float64            | [1;5]               | Average from post_A1, post_A2                                                                             |
| post_R_avg      | float64            | [1;5]               | Average from post_RV1, post_RV2                                                                           |
| post_C_avg      | float64            | [1;5]               | Average from post_C1, post_C2                                                                             |
| post_S_avg      | float64            | [1;5]               | Average rom post_S1, post_S2                                                                              |
