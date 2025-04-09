Hand Rotation Movement Dataset for Age-related Motor Skills Analysis
🧠 Background
Age-related differences in motor skills have been extensively studied, especially with increasing interest in utilizing behavioral data for cognitive assessment. Compared to traditional tools such as the MMSE (Mini-Mental State Examination) and CIST (Cognitive Impairment Screening Test), behavior-based assessment offers several advantages:

Shorter testing time

Less susceptibility to learning effects

Possibility of continuous, passive monitoring

Among behavioral signals, hand movements are promising due to fewer spatial constraints and ease of collection via webcams. This study explores hand rotation movements to determine whether they can reflect age-related differences in motor skill control — a step toward using behavioral indicators for early cognitive screening, such as mild cognitive impairment (MCI) detection.

🎯 Objective
This dataset and accompanying analysis aim to investigate:

Whether hand rotation movements can differentiate between two age groups:

Young adults (ages 20–29)

Older adults (ages 65–80)

If so, which motion-based indicators are most informative

We hypothesize that differences in hand motion control ability will exist, and propose seven hand motion indicators including:

Single-hand rotation speed

Time-based comparison between rotations

Angle-based comparison between rotations

🧪 Methods
Participants: 68 total

29 young adults (ages 20–29)

39 older adults (ages 65–80)

Task: Rotate both hands as quickly and accurately as possible for 10 seconds

Trials: 3 repetitions per hand, with 30-second rest intervals

Setup: Conducted via webcam, seated position

Data Format: Raw measurements include rotation angle sequences, timestamps, hand (left/right), trial number, and participant ID

Statistical Analysis: Generalized Estimation Equations (GEE) model

Between-subject factor: Age group

Within-subject factors: Hand (left/right), Trial (1/2/3)

Significance level: p < 0.05
