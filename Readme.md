# Awesome AI Sports Analytics

> A curated collection of **AI / ML / Computer Vision for sports analytics resources**: papers, datasets, github codes, benchmarks, competitions, Conferences and workshops. This README is a selective collection of high-quality resources for sports analytics AI from 2018 through 2026+ across soccer, basketball, American football, baseball, cricket, tennis, hockey, badminton, hammer throw, and multi-sport settings.
> > 
Check the readme or here https://ahmedeh28.github.io/Awesome-Sports-Analytics-AI/
> 
>
---

## 📋 Contents

- [⚽ Soccer / Football](#-soccer--football)
- [🏀 Basketball](#-basketball)
- [🏈 American Football](#-american-football)
- [⚾ Baseball](#-baseball)
- [🏏 Cricket](#-cricket)
- [🎾 Tennis](#-tennis)
- [🏒 Hockey](#-hockey)
- [🏸 Badminton / Racket Sports](#-badminton--racket-sports)
- [🤾 Hammer Throw](#-hammer-throw)
- [🌐 Multi-Sports](#-multi-sports)
- [🎓 Research Venues & Conferences](#-research-venues--conferences)
- [📖 Citation](#-citation)

---

## ⚽ Soccer / Football

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2018 | SoccerNet: A Scalable Dataset for Action Spotting in Soccer Videos | [Paper](https://arxiv.org/abs/1804.04527) | [Code](https://github.com/SilvioGiancola/SoccerNet-code) |
| 2021 | SoccerNet-v2: A Dataset and Benchmarks for Holistic Understanding of Broadcast Soccer Videos | [Paper](https://arxiv.org/abs/2011.13367) | [Code](https://github.com/SilvioGiancola/SoccerNetv2-DevKit) |
| 2021 | RMS-Net: Regression and Masking for Soccer Event Spotting | [Paper](https://arxiv.org/abs/2102.07624) | [Code](https://github.com/aimagelab/RMSNet_Soccer) |
| 2021 | Action Spotting and Temporal Attention Analysis in Soccer Videos | [Paper](https://doi.org/10.23919/MVA51890.2021.9511342) | - |
| 2022 | Automated Soccer Head Impact Exposure Tracking Using Video and Deep Learning | [Paper](https://www.nature.com/articles/s41598-022-13220-2) | - |
| 2023 | Towards Active Learning for Action Spotting in Association Football Videos | [Paper](https://openaccess.thecvf.com/content/CVPR2023W/CVSports/html/Giancola_Towards_Active_Learning_for_Action_Spotting_in_Association_Football_Videos_CVPRW_2023_paper.html) | - |
| 2024 | OSL-ActionSpotting: A Unified Library for Action Spotting in Sports Videos | [Paper](https://arxiv.org/abs/2407.01265) | [Code](https://github.com/OpenSportsLab/OSL-ActionSpotting) |
| 2024 | TacticAI: An AI Assistant for Football Tactics | [Paper](https://www.nature.com/articles/s41467-024-45965-x) | - |
| 2025 | Towards Universal Soccer Video Understanding | [Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Rao_Towards_Universal_Soccer_Video_Understanding_CVPR_2025_paper.html) | [Code](https://github.com/jyrao/UniSoccer) |
| 2025 | Multi-Agent System for Comprehensive Soccer Understanding | [Paper](https://arxiv.org/abs/2505.03735) | [Code](https://github.com/jyrao/SoccerAgent) |
| 2025 | FOOTPASS: A Multi-Modal Multi-Agent Tactical Context Dataset for Play-by-Play Action Spotting | [Paper](https://arxiv.org/abs/2511.16183) | [Code](https://github.com/JeremieOchin/FOOTPASS) |
| 2025 | Precise Event Spotting in Sports Videos: Solving Long-Range Dependency and Class Imbalance | [Paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Santra_Precise_Event_Spotting_in_Sports_Videos_Solving_Long_Range_Dependency_and_CVPR_2025_paper.pdf) | - |
| 2025 | SoccerNet 2025 Challenges Results | [Paper](https://arxiv.org/abs/2508.19182) | [Code](https://github.com/SoccerNet) |
| 2025 | Action Spotting and Precise Event Detection in Sports: Datasets, Methods, and Challenges | [Paper](https://arxiv.org/html/2505.03991v1) | - |
| 2026 | SoccerMaster: A Vision Foundation Model for Soccer Understanding | [Paper](https://arxiv.org/abs/2512.11016) | [Code](https://github.com/haolinyang-hlyang/SoccerMaster) |

### Datasets & Benchmarks

- **SoccerNet** (2018): 500 games · 764h · broadcast video + event labels. [Official](https://www.soccer-net.org/)
- **SoccerNet-v2** (2021): 500 games · >5M frames · spotting + replay grounding. [Official](https://silviogiancola.github.io/SoccerNetv2/)
- **SoccerNet Tracking** (2022): 12 games · 200 clips · tracking + IDs. [Official](https://www.soccer-net.org/)
- **SoccerNet ReID** (2023): 340,993 thumbnails · player re-identification. [Official](https://www.soccer-net.org/tasks/re-identification)
- **SoccerNet GSR** (2024): 200 clips · tracking + role + jersey + pitch coords. [Official](https://github.com/SoccerNet/sn-gamestate)
- **Wyscout Event Dataset** (2019): 7 competitions · spatio-temporal event logs. [Official](https://figshare.com/collections/Soccer_match_event_dataset/4415000)
- **StatsBomb Open Data** (—): Events + lineups + 360 freeze-frames. [Official](https://github.com/statsbomb/open-data)
- **Metrica Sample Data** (—): Tracking + event sample matches. [Official](https://github.com/metrica-sports/sample-data)

### Challenges & Competitions

- **SoccerNet Challenges** (2021-2026): Action spotting, tracking, re-id, GSR, calibration, captioning. [Official](https://www.soccer-net.org/challenges)

---

## 🏀 Basketball

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2019 | DeepHoops: Evaluating Micro-Actions in Basketball Using Deep Feature Representations of Spatio-Temporal Data | [Paper](https://dl.acm.org/doi/10.1145/3292500.3330719) | - |
| 2021 | Multi-Modal Trajectory Prediction of NBA Players | [Paper](https://openaccess.thecvf.com/content/WACV2021/papers/Hauri_Multi-Modal_Trajectory_Prediction_of_NBA_Players_WACV_2021_paper.pdf) | - |
| 2022 | Sports Video Analysis on Large-Scale Data: NBA Dataset for Automatic Highlight Generation and Commentating | [Paper](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136970019.pdf) | [Code](https://github.com/jackwu502/NSVA) |
| 2024 | PlayBest: Professional Basketball Player Behavior Synthesis via Planning with Diffusion | [Paper](https://dl.acm.org/doi/10.1145/3627673.3680092) | [Code](https://github.com/xiusic/diffuser_bball) |
| 2024 | FineSports: A Multi-person Hierarchical Sports Video Dataset for Fine-grained Action Understanding | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Xu_FineSports_A_Multi-person_Hierarchical_Sports_Video_Dataset_for_Fine-grained_Action_CVPR_2024_paper.pdf) | [Code](https://github.com/PKU-ICST-MIPL/FineSports_CVPR2024) |
| 2025 | TrackID3x3: Multi-Player Tracking with Identification and Pose Estimation in 3x3 Basketball | [Paper](https://dl.acm.org/doi/10.1145/3728423.3759400) | [Code](https://github.com/open-starlab/TrackID3x3) |

### Datasets & Benchmarks

- **APIDIS** (—): ~2h · 7 viewpoints · multi-view basketball video. [Official](https://ispgroup.gitlab.io/code/apidis/)
- **DeepSport Basketball-Instants** (2022): 300+ images · ball/player/court annotations. [Official](https://www.kaggle.com/datasets/gabrielvanzandycke/deepsport-dataset)
- **DeepSportRadar Instants** (2023): 700+ images · high-resolution annotated frames. [Official](https://www.kaggle.com/datasets/deepsportradar/basketball-instants-dataset)
- **BASKET** (2025): 4,477h · 32,232 players · 20 fine-grained skills. [Official](https://sites.google.com/cs.unc.edu/basket)

### Challenges & Competitions

- **DeepSportRadar Camera Calibration** (2022): 728 image/calibration pairs. [Official](https://deepsportradar.github.io/)
- **DeepSportRadar Instance Segmentation** (2023): Basketball instance segmentation challenge. [Official](https://mmsports.multimedia-computing.de/mmsports2023/challenge.html)
- **March Machine Learning Mania** (2014-2026): NCAA tournament prediction. [Official](https://www.kaggle.com/competitions/march-machine-learning-mania-2026)

---

## 🏈 American Football

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2019 | DeepQB: Deep Learning with Player Tracking to Quantify Quarterback Decision-Making and Performance | [Paper](https://www.sloansportsconference.com/research-papers/deepqb-deep-learning-with-player-tracking-to-quantify-quarterback-decision-making-performance) | - |
| 2020 | Expected Hypothetical Completion Probability | [Paper](https://arxiv.org/abs/1910.12337) | [Code](https://github.com/skdeshpande91/ehcp) |
| 2024 | NFL Ghosts: A Framework for Evaluating Defender Positioning with Conditional Density Estimation | [Paper](https://arxiv.org/abs/2406.17220) | [Code](https://github.com/ryurko/nfl-ghosts) |
| 2025 | Fractional Tackles: Leveraging Player Tracking Data for Within-Play Tackling Evaluation | [Paper](https://www.nature.com/articles/s41598-025-85993-1) | [Code](https://github.com/qntkhvn/tackle) |

### Datasets & Benchmarks

- **NFL Next Gen Stats** (—): Player + ball tracking · 10 Hz · 200+ metrics/play. [Official](https://operations.nfl.com/gameday/technology/nfl-next-gen-stats/)
- **Big Data Bowl Data** (2019): Tracking + game/play/player tables. [Official](https://github.com/nfl-football-ops/Big-Data-Bowl)
- **nflverse / nflreadr** (—): Open NFL data ecosystem. [Official](https://www.nflverse.com)

### Challenges & Competitions

- **NFL Big Data Bowl** (2019-2026): Annual tracking-based football analytics challenge. [Official](https://operations.nfl.com/gameday/analytics/big-data-bowl/)

---

## ⚾ Baseball

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2018 | Fine-Grained Activity Recognition in Baseball Videos | [Paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w34/Piergiovanni_Fine-Grained_Activity_Recognition_CVPR_2018_paper.pdf) | [Code](https://github.com/piergiaj/mlb-youtube) |
| 2024 | PitcherNet: Powering the Moneyball Evolution in Baseball Video Analytics | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/CVsports/papers/Bright_PitcherNet_Powering_the_Moneyball_Evolution_in_Baseball_Video_Analytics_CVPRW_2024_paper.pdf) | - |
| 2026 | A Data-Driven Analysis of Spatiotemporal Cues and Experience Accumulation Effects for Pitch Type Prediction | [Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0336554) | [Code](https://github.com/takamido/Pitch_type_pred_ML) |
| 2026 | Interpretable Pre-Release Baseball Pitch Type Anticipation from Markerless Motion Capture | [Paper](https://arxiv.org/abs/2603.04874) | - |

### Datasets & Benchmarks

- **Statcast / Baseball Savant** (2015-): Pitch, bat, batted-ball, fielding, running tracking. [Official](https://baseballsavant.mlb.com/)
- **Lahman Database** (2025): Historical MLB stats from 1871-2025. [Official](https://sabr.org/lahman-database/)

### Challenges & Competitions

- **MLB Player Digital Engagement Forecasting** (2021): MLB engagement prediction challenge. [Official](https://www.kaggle.com/competitions/mlb-player-digital-engagement-forecasting)
- **Diamond Dollars** (Annual): Baseball operations case competition. [Official](https://sabr.org/analytics/case)

---

## 🏏 Cricket

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2023 | Building Scalable Video Understanding Benchmarks through Sports Commentary Alignment | [Paper](https://arxiv.org/abs/2301.06866) | [Code](https://github.com/asap-benchmark/asap-pipeline) |
| 2023 | STAN: Spatial-Temporal Awareness Network for Cricket Action Detection | [Paper](https://dl.acm.org/doi/10.1145/3606038.3616169) | - |
| 2024 | Medium Scale Benchmark for Cricket Excited Actions Understanding | [Paper](https://openaccess.thecvf.com/content/CVPR2024W/CVsports/papers/Hussain_Medium_Scale_Benchmark_for_Cricket_Excited_Actions_Understanding_CVPRW_2024_paper.pdf) | [Code](https://github.com/Altaf-hucn/Cricket-Excited-Actions-Benchmark) |
| 2025 | I3D-AE-LSTM: A 2-Stream Autoencoder for Action Quality Assessment Using a Cricket Batsman Video Dataset | [Paper](https://openaccess.thecvf.com/content/WACV2025/papers/Moodley_I3D-AE-LSTM_A_2-Stream_Autoencoder_for_Action_Quality_Assessment_using_a_WACV_2025_paper.pdf) | [Code](https://github.com/dvanderhaar/uj-aqa-cricketvision) |
| 2025 | Modern Deep Learning Approaches for Cricket Shot Classification: A Comprehensive Baseline Study | [Paper](https://arxiv.org/abs/2510.09187) | [Code](https://github.com/hpicsk/CricShot10_Baselines) |
| 2026 | Automated Wicket-Taking Delivery Segmentation and Tactical Analysis in Cricket Broadcasts | [Paper](https://arxiv.org/abs/2510.18405) | - |

### Datasets & Benchmarks

- **Cricsheet** (—): 21,528 matches · ball-by-ball structured data. [Official](https://cricsheet.org/)
- **Cricsheet Register** (—): Player identity mapping. [Official](https://cricsheet.org/)
- **Cricsheet JSON Format** (—): Structured cricket data schema. [Official](https://cricsheet.org/format/json/)
- **cricketdata** (2025): R access package for Cricsheet + Cricinfo. [Official](https://pkg.robjhyndman.com/cricketdata/)

---

## 🎾 Tennis

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2019 | TrackNet: A Deep Learning Network for Tracking High-speed and Tiny Objects in Sports Applications | [Paper](https://arxiv.org/abs/1907.03698) | [Code](https://gitlab.nol.cs.nycu.edu.tw/open-source/TrackNet) |
| 2021 | Monocular Visual Analysis for Electronic Line Calling of Tennis | [Paper](https://arxiv.org/pdf/2107.09255) | - |
| 2023 | Learning Physically Simulated Tennis Skills from Broadcast Videos | [Paper](https://dl.acm.org/doi/10.1145/3592408) | [Code](https://github.com/nv-tlabs/vid2player3d) |
| 2025 | Where Is The Ball: 3D Ball Trajectory Estimation From 2D Monocular Tracking | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/CVSPORTS/papers/Ponglertnapakorn_Where_Is_The_Ball_3D_Ball_Trajectory_Estimation_From_2D_CVPRW_2025_paper.pdf) | - |

### Datasets & Benchmarks

- **TrackNet** (2019): Tennis ball tracking benchmark. [Official](https://arxiv.org/abs/1907.03698)
- **TenniSet** (2017): 5 matches · events + commentary captions. [Official](https://hayden.faulkner.codes/TenniSet)
- **Vid2Player3D** (2023): Broadcast-to-motion simulation benchmark. [Official](https://research.nvidia.com/labs/toronto-ai/vid2player3d/)
- **TrackNetV5 SDK** (2025): Tennis ball tracking SDK. [Official](https://github.com/codelancera-offical/TrackNetV5-SDK)

---

## 🏒 Hockey

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2021 | Puck Localization and Multi-Task Event Recognition in Broadcast Hockey Videos | [Paper](https://arxiv.org/abs/2105.10563) | - |
| 2021 | Automatic Play Segmentation of Hockey Videos | [Paper](https://openaccess.thecvf.com/content/CVPR2021W/CVSports/papers/Pidaparthy_Automatic_Play_Segmentation_of_Hockey_Videos_CVPRW_2021_paper.pdf) | - |
| 2021 | Player Tracking and Identification in Ice Hockey | [Paper](https://arxiv.org/pdf/2110.03090) | - |
| 2023 | Rink-Agnostic Hockey Rink Registration | [Paper](https://dl.acm.org/doi/10.1145/3606038.3616161) | - |
| 2025 | A Multi-Class Ice Hockey Dataset for Object Detection | [Paper](https://dl.acm.org/doi/10.1145/3712676.3718335) | [Code](https://github.com/acmmmsys/2025-HockeyAI) |
| 2025 | Ice Hockey Puck Localization Using Contextual Cues | [Paper](https://arxiv.org/abs/2506.04365) | - |

### Datasets & Benchmarks

- **NHL EDGE** (2021-22): Puck + player tracking platform. [Official](https://edge.nhl.com/)
- **MHPTD** (—): 25 clips · 82,305 frames · hockey tracking. [Official](https://github.com/grant81/hockeyTrackingDataset)
- **VIP-HTD** (2024): 22 clips · MOT hockey benchmark. [Official](https://github.com/harshap-ai/VIP-HTD)

---

## 🏸 Badminton / Racket Sports

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2021 | Exploring the Long Short-Term Dependencies to Infer Shot Influence in Badminton Matches | [Paper](https://arxiv.org/abs/2109.06431) | [Code](https://github.com/yao0510/Shot-Influence) |
| 2022 | MonoTrack: Shuttle Trajectory Reconstruction from Monocular Badminton Video | [Paper](https://arxiv.org/abs/2204.01899) | [Code](https://github.com/jhwang7628/monotrack) |
| 2023 | ShuttleSet: A Human-Annotated Stroke-Level Singles Dataset for Badminton Tactical Analysis | [Paper](https://arxiv.org/abs/2306.04948) | [Code](https://github.com/wywyWang/CoachAI-Projects/tree/main/ShuttleSet) |
| 2024 | Benchmarking Stroke Forecasting with Stroke-Level Badminton Dataset | [Paper](https://dl.acm.org/doi/10.24963/ijcai.2024/1042) | [Code](https://github.com/wywyWang/CoachAI-Projects/tree/main/CoachAI-Challenge-IJCAI2023) |
| 2024 | TrackNetV3: Enhancing ShuttleCock Tracking with Augmentations and Trajectory Rectification | [Paper](https://dl.acm.org/doi/10.1145/3595916.3626370) | [Code](https://github.com/qaz812345/TrackNetV3) |
| 2024 | The CoachAI Badminton Environment: A Novel Reinforcement Learning Environment for Tactical Decision Support | [Paper](https://dl.acm.org/doi/10.1609/aaai.v38i21.30523) | - |

### Datasets & Benchmarks

- **CoachAI / TrackNet** (2019): 18,242 frames · shuttle tracking. [Official](https://inoliao.github.io/CoachAI/)
- **ShuttleSet** (2023): 104 sets · 36,492 strokes. [Official](https://arxiv.org/abs/2306.04948)
- **ShuttleSet22** (2024): Extended stroke forecasting benchmark. [Official](https://arxiv.org/html/2306.15664v3)
- **CoachAI+** (2024): Badminton simulation environment. [Official](https://github.com/KuangDW/CoachAI-Plus)

### Challenges & Competitions

- **CoachAI Badminton Challenge** (2023): Forecasting and tactics tasks. [Official](https://sites.google.com/view/coachai-challenge-2023/)

---

## 🤾 Hammer Throw

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2026 | Hammer Throw Distance Estimation Using Deep Learning and Physics-Based Modeling | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417426009358) | [Code](https://github.com/AhmedEH28/Hammer-Throw-Distance-Estimation) |

### Datasets & Benchmarks

- **Olympic Sports (Hammer Throw)** (2014): Hammer throw class subset · 430 MB. [Official](https://vision.stanford.edu/Datasets/OlympicSports/)
- **Hammer Throw Distance Estimation** (2026): Video + 3D trajectory + physics modeling. [Official](https://ahmedeh28.github.io/hammerthrow/)

---

## 🌐 Multi-Sports

### Papers

| Year | Title | Paper | Code |
|------|-------|-------|------|
| 2023 | SportsMOT: A Large Multi-Object Tracking Dataset in Multiple Sports Scenes | [Paper](https://openaccess.thecvf.com/content/ICCV2023/html/Cui_SportsMOT_A_Large_Multi-Object_Tracking_Dataset_in_Multiple_Sports_Scenes_ICCV_2023_paper.html) | [Code](https://github.com/MCG-NJU/SportsMOT) |
| 2023 | Widely Applicable Strong Baseline for Sports Ball Detection and Tracking | [Paper](https://papers.bmvc2023.org/0310.pdf) | [Code](https://github.com/nttcom/WASB-SBDT) |
| 2024 | A Universal Protocol to Benchmark Camera Calibration for Sports | [Paper](https://arxiv.org/abs/2404.09807) | - |
| 2025 | SPORTU: A Comprehensive Sports Understanding Benchmark for Multimodal Large Language Models | [Paper](https://arxiv.org/abs/2410.08474) | - |
| 2025 | AthletePose3D: A Benchmark Dataset for 3D Human Pose Estimation and Kinematic Validation in Sports | [Paper](https://openaccess.thecvf.com/content/CVPR2025W/CVSPORTS/papers/Yeung_AthletePose3D_A_Benchmark_Dataset_for_3D_Human_Pose_Estimation_and_CVPRW_2025_paper.pdf) | - |

### Datasets & Benchmarks

- **Sports-1M** (2014): 1,133,158 videos · 487 sports labels. [Official](https://github.com/gtoderici/sports-1m-dataset)
- **MultiSports** (2021): ~3,200 clips · 37,701 actions · 902k boxes. [Official](https://deeperaction.github.io/datasets/multisports.html)
- **SportsMOT** (2023): 240 clips · basketball/football/volleyball MOT. [Official](https://deeperaction.github.io/datasets/sportsmot.html)
- **TeamTrack** (2024): 4M+ boxes · soccer/basketball/handball. [Official](https://atomscott.github.io/TeamTrack/)

---

## 🎓 Research Venues & Conferences

| Venue | Description | Link |
|-------|-------------|------|
| **CVSports @ CVPR** | Main computer vision in sports workshop | [Official](https://vap.aau.dk/cvsports/11th-international-workshop-on-computer-vision-in-sports-cvsports-at-cvpr-2025/) |
| **ACM MMSports** | Multimedia analysis in sports workshop | [Official](https://mmsports.multimedia-computing.de/mmsports2025/index.html) |
| **MIT Sloan Sports Analytics Conference** | Broad sports analytics venue | [Official](https://www.sloansportsconference.com/conference/2026-conference) |
| **Carnegie Mellon Sports Analytics Conference** | Academic sports analytics conference | [Official](https://www.cmsaconference.com/) |
| **MathSport International** | Math, operations research, and sports analytics | [Official](https://math.uni.lu/midas/events/mathsports2025/) |
| **ASA Virtual Sports Analytics Conference** | Sports data science conference | [Official](https://instats.org/seminar/asa-sports-analytics-conference) |
| **SABR Analytics Conference** | Baseball analytics conference | [Official](https://sabr.org/analytics/) |
| **CVPR Workshops Index** | Workshop discovery and proceedings | [Official](https://cvpr.thecvf.com/Conferences/2026/Workshops) |

---

## 📖 Citation

If you find this repository useful, please consider citing:

```bibtex
@misc{ahmed2026awesome_sports_ai,
  title  = {Awesome-Sports-Analytics-AI},
  author = {Ahmed Endris},
  year   = {2026},
  url    = {https://github.com/AhmedEH28/Awesome-Sports-Analytics-AI},
  note   = {GitHub repository}
}
```

---

## 🤝 Contribution

Contributions are welcome! If you know of a paper, dataset, or competition that belongs here, please Contribute and If you find it useful please ⭐, THANKS!
---


