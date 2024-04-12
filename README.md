# Minor-Project
Adversarial Filter for Deepfake Prevention

@article{wang2022anti,
  title={Anti-Forgery: Towards a Stealthy and Robust DeepFake Disruption Attack via Adversarial Perceptual-aware Perturbations},
  author={Wang, Run and Huang, Ziheng and Chen, Zhikai and Liu, Li and Chen, Jing and Wang, Lina},
  journal={arXiv preprint arXiv:2206.00477},
  year={2022}
}

#### Step 1 : git clone https://github.com/shashwatsrii/Minor-Project/tree/main
## For Lab Color Space 
#### Step 2 : cd LabColorSpace
#### Step 3 : pip install -r requirements.txt
#### Step 4 : icacls download.sh /grant Everyone:RX
#### Step 5 : bash download.sh celeba
#### Step 6 : python main.py --mode test --image_size 256 --c_dim 5 --selected_attrs Black_Hair Blond_Hair Brown_Hair Male Young --model_save_dir='stargan_celeba_256/models' --result_dir='./results' --test_iters 200000 --attack_iters 100 --batch_size 1