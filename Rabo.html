<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Editor + Calculator</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        h1 {
            text-align: center;
            color: #2c3e50;
        }

        .tabs {
            display: flex;
            margin-bottom: 20px;
            justify-content: center;
        }

        .tab-button {
            padding: 10px 20px;
            background-color: #ecf0f1;
            border: none;
            cursor: pointer;
            font-size: 16px;
            transition: all 0.3s;
        }

        .tab-button:hover {
            background-color: #bdc3c7;
        }

        .tab-button.active {
            background-color: #3498db;
            color: white;
        }

        .tab-content {
            display: none;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .tab-content.active {
            display: block;
        }

        /* Image Editor Styles */
        .editor-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        .controls {
            flex: 1;
            min-width: 250px;
        }

        .image-preview {
            flex: 2;
            min-width: 300px;
        }

        #preview-image {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        .slider-group {
            margin-bottom: 15px;
        }

        .slider-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .slider-group input[type="range"] {
            width: 100%;
        }

        button {
            padding: 8px 15px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            margin: 5px;
            font-size: 14px;
        }

        button:hover {
            background-color: #2980b9;
        }

        #download-btn {
            background-color: #27ae60;
        }

        #download-btn:hover {
            background-color: #219653;
        }

        #reset-btn {
            background-color: #e74c3c;
        }

        #reset-btn:hover {
            background-color: #c0392b;
        }

        /* Calculator Styles */
        .calculator {
            max-width: 300px;
            margin: 0 auto;
            background-color: #34495e;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        #calc-display {
            width: 100%;
            padding: 10px;
            font-size: 24px;
            text-align: right;
            margin-bottom: 15px;
            background-color: #ecf0f1;
            border: none;
            border-radius: 5px;
        }

        .calc-buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
        }

        .calc-buttons button {
            padding: 15px;
            font-size: 18px;
            background-color: #2c3e50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .calc-buttons button:hover {
            background-color: #1a252f;
        }

        .clear-btn {
            background-color: #e74c3c !important;
        }

        .clear-btn:hover {
            background-color: #c0392b !important;
        }

        @media (max-width: 768px) {
            .editor-container {
                flex-direction: column;
            }
            
            .controls, .image-preview {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Image Editor with Calculator</h1>
        
        <div class="tabs">
            <button class="tab-button active" onclick="openTab('image-editor')">Image Editor</button>
            <button class="tab-button" onclick="openTab('calculator')">Calculator</button>
        </div>
        
        <div id="image-editor" class="tab-content active">
            <div class="editor-container">
                <div class="controls">
                    <input type="file" id="image-upload" accept="image/*">
                    <div class="slider-group">
                        <label for="brightness">Brightness</label>
                        <input type="range" id="brightness" min="0" max="200" value="100">
                    </div>
                    <div class="slider-group">
                        <label for="contrast">Contrast</label>
                        <input type="range" id="contrast" min="0" max="200" value="100">
                    </div>
                    <div class="slider-group">
                        <label for="saturation">Saturation</label>
                        <input type="range" id="saturation" min="0" max="200" value="100">
                    </div>
                    <div class="slider-group">
                        <label for="hue">Hue</label>
                        <input type="range" id="hue" min="0" max="360" value="0">
                    </div>
                    <div class="slider-group">
                        <label for="blur">Blur</label>
                        <input type="range" id="blur" min="0" max="10" value="0">
                    </div>
                    <button id="reset-btn">Reset Filters</button>
                    <button id="download-btn">Download Image</button>
                </div>
                <div class="image-preview">
                    <img id="preview-image" src="https://via.placeholder.com/500x300?text=Upload+an+image" alt="Preview">
                </div>
            </div>
        </div>
        
        <div id="calculator" class="tab-content">
            <div class="calculator">
                <input type="text" id="calc-display" disabled>
                <div class="calc-buttons">
                    <button onclick="appendToDisplay('7')">7</button>
                    <button onclick="appendToDisplay('8')">8</button>
                    <button onclick="appendToDisplay('9')">9</button>
                    <button onclick="appendToDisplay('/')">/</button>
                    
                    <button onclick="appendToDisplay('4')">4</button>
                    <button onclick="appendToDisplay('5')">5</button>
                    <button onclick="appendToDisplay('6')">6</button>
                    <button onclick="appendToDisplay('*')">×</button>
                    
                    <button onclick="appendToDisplay('1')">1</button>
                    <button onclick="appendToDisplay('2')">2</button>
                    <button onclick="appendToDisplay('3')">3</button>
                    <button onclick="appendToDisplay('-')">-</button>
                    
                    <button onclick="appendToDisplay('0')">0</button>
                    <button onclick="appendToDisplay('.')">.</button>
                    <button onclick="calculate()">=</button>
                    <button onclick="appendToDisplay('+')">+</button>
                    
                    <button onclick="clearDisplay()" class="clear-btn">C</button>
                    <button onclick="backspace()" class="clear-btn">⌫</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        // Tab functionality
        function openTab(tabName) {
            const tabContents = document.getElementsByClassName("tab-content");
            for (let i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }
            
            const tabButtons = document.getElementsByClassName("tab-button");
            for (let i = 0; i < tabButtons.length; i++) {
                tabButtons[i].classList.remove("active");
            }
            
            document.getElementById(tabName).classList.add("active");
            event.currentTarget.classList.add("active");
        }

        // Image Editor Functionality
        document.addEventListener('DOMContentLoaded', function() {
            const imageUpload = document.getElementById('image-upload');
            const previewImage = document.getElementById('preview-image');
            const brightnessSlider = document.getElementById('brightness');
            const contrastSlider = document.getElementById('contrast');
            const saturationSlider = document.getElementById('saturation');
            const hueSlider = document.getElementById('hue');
            const blurSlider = document.getElementById('blur');
            const resetBtn = document.getElementById('reset-btn');
            const downloadBtn = document.getElementById('download-btn');
            
            let currentImage = null;
            
            // Upload image
            imageUpload.addEventListener('change', function(e) {
                const file = e.target.files[0];
                if (file) {
                    const reader = new FileReader();
                    reader.onload = function(event) {
                        previewImage.src = event.target.result;
                        currentImage = previewImage.src;
                        applyFilters();
                    };
                    reader.readAsDataURL(file);
                }
            });
            
            // Apply filters when sliders change
            [brightnessSlider, contrastSlider, saturationSlider, hueSlider, blurSlider].forEach(slider => {
                slider.addEventListener('input', applyFilters);
            });
            
            // Apply all filters
            function applyFilters() {
                const brightness = brightnessSlider.value;
                const contrast = contrastSlider.value;
                const saturation = saturationSlider.value;
                const hue = hueSlider.value;
                const blur = blurSlider.value;
                
                previewImage.style.filter = `
                    brightness(${brightness}%)
                    contrast(${contrast}%)
                    saturate(${saturation}%)
                    hue-rotate(${hue}deg)
                    blur(${blur}px)
                `;
            }
            
            // Reset filters
            resetBtn.addEventListener('click', function() {
                brightnessSlider.value = 100;
                contrastSlider.value = 100;
                saturationSlider.value = 100;
                hueSlider.value = 0;
                blurSlider.value = 0;
                applyFilters();
            });
            
            // Download image
            downloadBtn.addEventListener('click', function() {
                if (!currentImage) {
                    alert('Please upload an image first');
                    return;
                }
                
                const canvas = document.createElement('canvas');
                const ctx = canvas.getContext('2d');
                canvas.width = previewImage.naturalWidth;
                canvas.height = previewImage.naturalHeight;
                
                // Apply filters to canvas
                ctx.filter = previewImage.style.filter;
                ctx.drawImage(previewImage, 0, 0, canvas.width, canvas.height);
                
                // Create download link
                const link = document.createElement('a');
                link.download = 'edited-image.png';
                link.href = canvas.toDataURL('image/png');
                link.click();
            });
        });

        // Calculator Functionality
        let displayValue = '0';

        function updateDisplay() {
            document.getElementById('calc-display').value = displayValue;
        }

        function appendToDisplay(value) {
            if (displayValue === '0' && value !== '.') {
                displayValue = value;
            } else {
                displayValue += value;
            }
            updateDisplay();
        }

        function clearDisplay() {
            displayValue = '0';
            updateDisplay();
        }

        function backspace() {
            if (displayValue.length === 1) {
                displayValue = '0';
            } else {
                displayValue = displayValue.slice(0, -1);
            }
            updateDisplay();
        }

        function calculate() {
            try {
                // Replace × with * for evaluation
                const expression = displayValue.replace(/×/g, '*');
                displayValue = eval(expression).toString();
                updateDisplay();
            } catch (error) {
                displayValue = 'Error';
                updateDisplay();
                setTimeout(clearDisplay, 1000);
            }
        }

        // Initialize calculator display
        updateDisplay();
    </script>
</body>
</html>
