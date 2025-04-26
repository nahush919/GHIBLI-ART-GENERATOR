# TRY YOUR GHIBLI'S

✨ Transform your photos into stunning Studio Ghibli-style artworks!  
This project leverages the power of Stable Diffusion models to reimagine real-world images with dreamy, colorful Ghibli aesthetics.

---

## 🚀 Features

- Convert any photo into Ghibli-style artwork
- Easy-to-use Google Colab notebook (no installation hassle)
- Supports custom prompts for creative flexibility
- Based on **Waifu Diffusion** model fine-tuned for anime and soft artistic styles

---

## 🛠️ Tech Stack

- Python
- OpenCV
- Diffusers (Hugging Face)
- Hugging Face Transformers
- PIL (Python Imaging Library)
- SciPy
- Google Colab

---

## 📷 Sample Outputs and Inputs with Prompt
Sample 1:Cherry Blossom at Megumo River,tokyo

prompt:A serene evening along Tokyo's Meguro River, where cherry blossom trees arch over the water, their petals illuminated by soft lantern light. The gentle flow of the river reflects the pink hues, creating a magical atmosphere reminiscent of a Studio Ghibli scene."

![Screenshot 2025-04-26 182242](https://github.com/user-attachments/assets/799e39a5-0366-4565-9f79-0a1ff47831d4)

Sample 2:Torii Gate in Nature

prompt:"A peaceful ancient torii gate pathway in a misty Japanese forest, surrounded by moss-covered trees, soft magical light breaking through, Ghibli-style enchanted anime art."

![Screenshot 2025-04-26 190317](https://github.com/user-attachments/assets/0f8b024c-9528-40a3-a51e-b7d550a90cc8)

Sample 3:Lake Scene with Mount Fuji

prompt:"A calm serene lake reflecting Mount Fuji during a pastel-colored sunrise, soft mist, few distant cherry trees blooming, peaceful atmosphere, highly detailed dreamy Studio Ghibli anime style."

![Screenshot 2025-04-26 190919](https://github.com/user-attachments/assets/36989f68-5aae-4ff1-a962-83d1a64be2ef)

Sample 4:Old Traditional Japanese Town

prompt:"A narrow old Japanese village street, traditional wooden houses with paper lanterns, cozy warm atmosphere, evening setting sun, Ghibli fantasy detailed anime art style."

![image](https://github.com/user-attachments/assets/0668b995-89ee-4445-8b84-4909bacb25cd)

Sample 5:A man walking on a mountain path

prompt = "A  man standing walking towards  mountain, surrounded by soft sunlight and gentle trees, warm atmosphere, dreamy countryside, trekking,rocky path, Studio Ghibli art style, soft pastel colors, magical realism,litlle foggy and he's trekking"

![image](https://github.com/user-attachments/assets/754340ec-4a46-482f-919c-4680e421c7b8)








---

## ⚙️ Installation and Setup

This project is best run on **Google Colab** (free GPU provided).

### Quick Steps:
1. Open the Colab notebook.
2. Upload your input image(s).
3. Install required libraries:
    ```bash
    pip install diffusers transformers accelerate scipy safetensors
    ```
4. Load the Waifu Diffusion model.
5. Enter your creative prompt and run the generation cell.
6. Save and download your output!

> **Note:**  
> Make sure you have a stable internet connection while running the model, as it requires downloading weights and running computations on GPU.

---

## ✨ Credits

- Model: [Waifu Diffusion](https://huggingface.co/hakurei/waifu-diffusion)
- Diffusers Library: Hugging Face Team
- Images inspired by the works of Studio Ghibli.

---

## 📄 License

This project is intended **for personal, academic, and non-commercial use only**.

---

## ❓ FAQ

### Can you explain the code cell-by-cell?

Yes!  
The project is divided into simple cells, each performing a specific task:

| Step | Description |
|:---|:---|
| 1 | Install necessary Python libraries |
| 2 | Import libraries (Diffusers, PIL, etc.) |
| 3 | Load the Waifu Diffusion model into memory |
| 4 | Define input and output image paths |
| 5 | Load your input image and resize it |
| 6 | Define your artistic prompt |
| 7 | Generate the new Ghibli-style image |
| 8 | Save and display the output |

Every step is modular, so you can run them separately without repeating heavy downloads.

If you need a **detailed, deep explanation cell-by-cell**, feel free to check the code comments inside the notebook or contact me!

---

## 📬 Contact

Feel free to reach out for any questions or collaborations!

---
