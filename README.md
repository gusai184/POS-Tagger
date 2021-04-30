# POS-Tagger
POS tagging is a very basic task in NLP and Computational Linguistics. However, as many of you already know, the state of POS tagging for Indian Languages is quite a mess at the moment. 

This project has two subparts:
<ul>
  <li> Implementation of HMM or CRF as Basline POS Tagging Technique. </li>
  <li> Implementation of Neural Based POS Tagging Technique. </li>
</ul>

Directory Structure:
  ```
  ├── database                                // Dataset
    ├── guj_art and culture_sample1.txt
    ├── guj_economy_sample2.txt
    ├── guj_entertainment_sample3.txt
    ├── guj_philosophy_sample4.txt
    ├── guj_religion_sample5.txt
    ├── guj_science and technology_sample6.txt
    ├── guj_sports_sample7.txt
  ├── POSTaggerCRF.ipynb                      // Source code for CRF POS Tagger      
  ├── POSTaggerHMM.ipynb                      // Source code for HMM POS Tagger 
  ├── POSTaggerRNN.ipynb                      // Source code for RNN POS Tagger
  ├── CRF_report.pkl                          // CRF evalution metrics
  ├── HMM_report.pkl                          // HMM evalution metrics
  ├── rnn_report.pkl                          // RNN evalution metrics
  ├── lstm_report.pkl                         // LSTM evalution metrics
  ├── bilstm_report.pkl                       // BiLSTM evalution metrics
  ├── POSTagger.pdf                           // Project Presentation    
  ├── report.pdf                              // Project Report
  ├── project_outline.pdf                     // Project Outline
  ├── Tagset.pdf                              // Tagset for Gujarati Language 
  ├── rnn_model.hdf5                          // Saved LSTM Model
  └── README.md
  ```
GitHub Link : https://github.com/gusai184/POS-Tagger
