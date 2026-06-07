# Unitree G1 Course — Notebooks

Cwiczenia Colab do kursu programowania robotow Unitree G1 i Go2
([LucsRobotics](https://lucsrobotics.pl)). Kazdy notebook dziala w darmowym
Google Colab — bez instalacji, bez GPU (chyba ze zaznaczono inaczej).

| Notebook | Modul kursu | Co robisz |
|---|---|---|
| `ex0_g1_standing.ipynb` | M0 | MuJoCo + model G1: inspekcja, PD hold, test pchniecia 200 N |
| `ex1_pd_tuning.ipynb` | M1 | Strojenie kp/kd na pojedynczym stawie, odpowiedz skokowa |
| `ex2_reward_concepts.ipynb` | M2 | Funkcje nagrod RL na danych przykladowych |
| `ex2_train_gait.ipynb` | M2 | Analiza treningu polityki chodu (metryki, krzywe) |
| `ex3_motion_tracking.ipynb` | M3 | Pozy → trajektoria → eksport trajectory.json do symulatora kursu |
| `ex5_apriltag.ipynb` | M5 | Detekcja AprilTag + pozycja 6DOF |
| `ex5_yolo_detect.ipynb` | M5 | YOLO11: detekcja obiektow + deprojekcja do 3D |
| `ex7_lerobot_explore.ipynb` | M7 | Eksploracja prawdziwego datasetu LeRobot z HF: struktura, trajektorie, ocena jakosci |
| `ex8_gemini_scene.ipynb` | M8 | Gemini Robotics-ER jako planer scen (darmowy klucz AI Studio) |
| `ex8_unifolm_eval.ipynb` | M8 | Porownanie architektur VLA, metadane modeli z HF |

## Jak korzystac

Najprosciej: przyciski "Otworz w Colab" w aplikacji kursu. Recznie:
`https://colab.research.google.com/github/lgruszka/g1-course-notebooks/blob/main/notebooks/<nazwa>.ipynb`

## Licencja

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) —
mozesz uzywac i modyfikowac do celow niekomercyjnych z podaniem zrodla.
Wykorzystanie komercyjne (np. w platnych szkoleniach): kontakt
lucs.robotics@gmail.com.

(c) dr inz. Lukasz Gruszka · LucsRobotics
