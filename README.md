# Task 9 :-
# Time-Based Historical Image Colorization Description: 


🎯 Key Features :-


🧠 Era Classification: Automatically classifies images into historical periods using a CNN-based classifier.

🎨 Time-Specific Colorization: Uses colorization models or palettes tailored to specific eras (e.g., muted WWII tones vs. vibrant 1950s).

🖼️ GUI Interface:

Upload grayscale photo

Automatically detect historical era

Option to manually override era selection

View final colorized result


🧠 Techniques Used :-


Era Classification Model: Trained on labeled historical photos using ResNet-18 or EfficientNet.

Conditional Colorization:

A single model with multi-era conditioning, or

Separate colorization models trained per era

Palette Mapping: Style transfer or learned palette matching for each time period

Streamlit or Tkinter GUI for interactive use


📊 Dataset


You can use:

[DeOldify Dataset Extensions]

[Flickr Historical Archive]

[ImageNet Grayscale Subsets]

Split the dataset into historical categories (1900s, 1920s, 1950s, etc.) using metadata or manual annotation for training the classifier.

🛠️ How It Works

Upload a Grayscale Photo

Era Detection (via classifier)

Colorization

Loads corresponding model or palette

Applies colorization based on the detected era

User Option to Override Era

Download Result

🙏 Acknowledgements

DeOldify

ImageColorization-Papers

OpenCV, PyTorch, Streamlit, and TensorFlow communities



