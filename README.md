# Analisis Proses Belajar Mahasiswa Menggunakan Process Mining dan Machine Learning

Repositori ini berisi kode program Tugas Akhir untuk menganalisis proses belajar mahasiswa pada Learning Management System (LMS) menggunakan pendekatan **Process Mining** dan **Machine Learning**.

## Deskripsi

Penelitian ini bertujuan untuk menganalisis pola aktivitas belajar mahasiswa berdasarkan event log LMS. Pendekatan **Process Mining** digunakan untuk menemukan alur proses belajar mahasiswa, sedangkan **Machine Learning** digunakan untuk mengklasifikasikan performa akademik mahasiswa berdasarkan fitur proses yang diekstraksi dari event log.

Metode yang digunakan dalam penelitian ini meliputi:

- Process Mining
- Directly-Follows Graph (DFG)
- Inductive Miner
- Process Tree
- Petri Net
- Conformance Checking
- Logistic Regression
- Random Forest

## Struktur Notebook

```text
01_data_understanding.ipynb
02_prepare_label_performance.ipynb
03_preprocessing_event_log.ipynb
04_full_log_vs_compact_log.ipynb
05_dfg_visualization.ipynb
06_process_discovery_inductive_miner.ipynb
07_conformance_checking.ipynb
08_feature_extraction.ipynb
09_learning_pattern_by_performance.ipynb
10_ml_dataset_preparation.ipynb
11_model_training_evaluation.ipynb
12_model_optimization.ipynb
13_final_result_summary.ipynb
14_process_mining_by_performance_group.ipynb
