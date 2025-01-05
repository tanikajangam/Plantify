# Plantify – Diagnosing Plant Diseases with AI  

Plantify is an AI-powered application designed to identify and classify plant leaf diseases with high accuracy. By uploading a photo of a plant leaf, users receive instant feedback on the health of the plant, along with disease descriptions, prevention tips, and recommended supplements to restore plant vitality.  

🔗 **[Devpost Project Page](https://devpost.com/software/plantify-5pu2n1)**  

---  

## Inspiration  
Plant leaf diseases can significantly impact agricultural productivity and economic stability. Recognizing and classifying these diseases early can help conserve plant species and mitigate economic loss. Plantify leverages cutting-edge AI to promote healthier plants and support a thriving ecosystem in our increasingly tech-driven world.  

---  

## What is Plantify?  
Built on a convolutional neural network (CNN), Plantify identifies plant diseases by analyzing uploaded images of plant leaves. Key features include:  
- **Photo Upload** – Snap and upload an image of a plant leaf.  
- **Disease Identification** – Get real-time insights into plant health and detect diseases.  
- **Disease Prevention** – Receive descriptions and preventive measures for identified diseases.  
- **Supplement Recommendations** – Suggests fertilizers or supplements to treat the disease, with direct links for purchase.  

---  

## How We Built It  
Plantify utilizes:  
- **AI Model** – Trained with over 6,000 images across 39 categories using PyTorch.  
- **Backend** – Flask server integrated with a Jinja-powered frontend.  
- **UI/UX Design** – Designed with Figma and CSS for a seamless experience.  

The model was developed and tested on Jupyter Notebook, optimizing for high accuracy (95%) in disease classification and real-time diagnosis.  

---  

## Tech Stack  
- **AI/ML**: PyTorch  
- **Backend**: Flask  
- **Frontend**: Jinja, CSS  
- **Design**: Figma  
- **Tools**: Jupyter Notebook  

---  

## Challenges We Faced  
- Neural Network Architecture – Determining the correct CNN architecture posed initial difficulties.  
- Long Training Times – Processing large datasets without GPU/TPU significantly slowed model training.  
- Overcoming Complexity – By implementing batch gradient descent with softmax activation, the model was successfully trained on time.  

---  

## Accomplishments We're Proud Of  
Plantify doesn't stop at classification – it goes the extra mile by recommending treatments and resources. This end-to-end solution helps users not only diagnose but also treat and revive their plants.  

---  

## What's Next for Plantify  
Future enhancements include:  
- **E-commerce Integration** – Allow users to purchase supplements directly through the app.  
- **Community Features** – Share and discuss plant care tips with other users.  
- **Scalability** – Expand Plantify's plant database to cover more species and diseases.  

---  

## Demo  
Interested in seeing Plantify in action?  
🔗 **[Devpost Link](https://devpost.com/software/plantify-5pu2n1)**  

---  

## How to Run It Locally  
```bash
# Clone the repository
git clone https://github.com/tanikajangam/plantify

# Navigate to the project directory
cd plantify

# Install dependencies
pip install -r requirements.txt

# Start the Flask server
flask run
