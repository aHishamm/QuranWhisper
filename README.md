# QuranWhisper
This is a project to evaluate the performance of different fine-tuned neural ASR systems.  
#### Evaluation Metrics 
1. Model Inference Time 
2. Word error rate (WER) 
3. Match error rate (MER) 
4. Word information Preserved (WIP) 
5. Character error rate (CER) 
#### Included Models 
1. OpenAI Whisper Large 
2. arbml/whisper-largev2-ar
3. tarteel-ai/whisper-base-ar-quran
4. tarteel-ai/whisper-tiny-ar-quran


#### Environment setup 
1. Assuming Conda is installed, create a new conda environment: 
```bash
conda create -n quranwhisper python=3.10 
conda activate quranwhisper 
``` 
2. Install the required packages: 
```bash
pip install -r requirements.txt 
```
3. Add the recitation audio files in the root directory of the project, as shown below: 
```bash
    .
    ├── ...
    ├── recitations                    
    │   ├── aya1.wav          
    │   ├── aya2.wav         
    │   └── ...                
    └── ...
```