<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watermark Maker</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            min-height: 100vh;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            max-width: 1200px;
            width: 100%;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            margin-top: 20px;
        }

        header {
            background: #4a6fa5;
            color: white;
            padding: 20px;
            text-align: center;
        }

        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1rem;
            opacity: 0.9;
        }

        .app-content {
            display: flex;
            flex-wrap: wrap;
            padding: 20px;
            gap: 20px;
        }

        .controls {
            flex: 1;
            min-width: 300px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
        }

        .preview {
            flex: 2;
            min-width: 400px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: #f8f9fa;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            padding: 20px;
        }

        .control-group {
            margin-bottom: 20px;
        }

        h2 {
            font-size: 1.3rem;
            color: #4a6fa5;
            margin-bottom: 15px;
            padding-bottom: 5px;
            border-bottom: 2px solid #eaeaea;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
            color: #555;
        }

        input, select, button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }

        input[type="color"] {
            height: 40px;
            padding: 3px;
        }

        .range-container {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .range-value {
            min-width: 40px;
            text-align: center;
            font-weight: bold;
            color: #4a6fa5;
        }

        button {
            background: #4a6fa5;
            color: white;
            border: none;
            cursor: pointer;
            font-weight: 600;
            transition: background 0.3s;
            padding: 12px;
            margin-top: 10px;
        }

        button:hover {
            background: #3a5a80;
        }

        #saveBtn {
            background: #2e7d32;
        }

        #saveBtn:hover {
            background: #1b5e20;
        }

        #resetBtn {
            background: #d32f2f;
        }

        #resetBtn:hover {
            background: #b71c1c;
        }

        .canvas-container {
            width: 100%;
            max-width: 600px;
            height: 400px;
            border: 2px dashed #ccc;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            background: #f0f0f0;
            margin-bottom: 20px;
        }

        #previewCanvas {
            max-width: 100%;
            max-height: 100%;
            display: none;
        }

        .placeholder {
            text-align: center;
            color: #888;
            padding: 20px;
        }

        .placeholder i {
            font-size: 3rem;
            margin-bottom: 10px;
            color: #4a6fa5;
        }

        .image-info {
            margin-top: 10px;
            text-align: center;
            color: #666;
            font-style: italic;
        }

        footer {
            text-align: center;
            padding: 20px;
            color: #666;
            font-size: 0.9rem;
            margin-top: 20px;
        }

        @media (max-width: 768px) {
            .app-content {
                flex-direction: column;
            }
            
            .controls, .preview {
                min-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Watermark Maker</h1>
            <p class="subtitle">Add custom text watermarks to your images</p>
        </header>
        
        <div class="app-content">
            <div class="controls">
                <div class="control-group">
                    <h2>Image Upload</h2>
                    <input type="file" id="imageUpload" accept="image/*">
                    <button id="loadBtn">Load Image</button>
                </div>
                
                <div class="control-group">
                    <h2>Watermark Text</h2>
                    <label for="watermarkText">Watermark Text:</label>
                    <input type="text" id="watermarkText" value="Your Watermark" placeholder="Enter watermark text">
                    
                    <label for="fontSize">Font Size:</label>
                    <div class="range-container">
                        <input type="range" id="fontSize" min="10" max="100" value="36">
                        <span class="range-value" id="fontSizeValue">36</span>
                    </div>
                    
                    <label for="textColor">Text Color:</label>
                    <input type="color" id="textColor" value="#ffffff">
                    
                    <label for="opacity">Opacity:</label>
                    <div class="range-container">
                        <input type="range" id="opacity" min="0" max="100" value="70">
                        <span class="range-value" id="opacityValue">70%</span>
                    </div>
                </div>
                
                <div class="control-group">
                    <h2>Position & Rotation</h2>
                    <label for="position">Position:</label>
                    <select id="position">
                        <option value="top-left">Top Left</option>
                        <option value="top-right">Top Right</option>
                        <option value="bottom-left">Bottom Left</option>
                        <option value="bottom-right" selected>Bottom Right</option>
                        <option value="center">Center</option>
                        <option value="tiled">Tiled (Pattern)</option>
                    </select>
                    
                    <label for="rotation">Rotation (degrees):</label>
                    <div class="range-container">
                        <input type="range" id="rotation" min="0" max="360" value="0">
                        <span class="range-value" id="rotationValue">0°</span>
                    </div>
                </div>
                
                <div class="control-group">
                    <h2>Actions</h2>
                    <button id="applyBtn">Apply Watermark</button>
                    <button id="saveBtn">Save Image</button>
                    <button id="resetBtn">Reset</button>
                </div>
            </div>
            
            <div class="preview">
                <div class="canvas-container">
                    <canvas id="previewCanvas"></canvas>
                    <div class="placeholder" id="canvasPlaceholder">
                        <i>📷</i>
                        <p>Upload an image to get started</p>
                    </div>
                </div>
                <p class="image-info" id="imageInfo">No image loaded</p>
            </div>
        </div>
        
        <footer>
            <p>Watermark Maker &copy; 2023 | Add professional watermarks to your images</p>
        </footer>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // DOM elements
            const imageUpload = document.getElementById('imageUpload');
            const loadBtn = document.getElementById('loadBtn');
            const applyBtn = document.getElementById('applyBtn');
            const saveBtn = document.getElementById('saveBtn');
            const resetBtn = document.getElementById('resetBtn');
            const previewCanvas = document.getElementById('previewCanvas');
            const canvasPlaceholder = document.getElementById('canvasPlaceholder');
            const imageInfo = document.getElementById('imageInfo');
            
            // Watermark controls
            const watermarkText = document.getElementById('watermarkText');
            const fontSize = document.getElementById('fontSize');
            const fontSizeValue = document.getElementById('fontSizeValue');
            const textColor = document.getElementById('textColor');
            const opacity = document.getElementById('opacity');
            const opacityValue = document.getElementById('opacityValue');
            const position = document.getElementById('position');
            const rotation = document.getElementById('rotation');
            const rotationValue = document.getElementById('rotationValue');
            
            // Canvas context
            const ctx = previewCanvas.getContext('2d');
            
            // Image variables
            let originalImage = null;
            let watermarkedImage = null;
            
            // Update range value displays
            fontSize.addEventListener('input', function() {
                fontSizeValue.textContent = fontSize.value;
            });
            
            opacity.addEventListener('input', function() {
                opacityValue.textContent = opacity.value + '%';
            });
            
            rotation.addEventListener('input', function() {
                rotationValue.textContent = rotation.value + '°';
            });
            
            // Load image
            loadBtn.addEventListener('click', function() {
                if (imageUpload.files.length === 0) {
                    alert('Please select an image file first!');
                    return;
                }
                
                const file = imageUpload.files[0];
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    const img = new Image();
                    img.onload = function() {
                        originalImage = img;
                        
                        // Set canvas dimensions to match image
                        previewCanvas.width = img.width;
                        previewCanvas.height = img.height;
                        
                        // Display the image
                        ctx.drawImage(img, 0, 0);
                        
                        // Show canvas and hide placeholder
                        previewCanvas.style.display = 'block';
                        canvasPlaceholder.style.display = 'none';
                        
                        // Update image info
                        imageInfo.textContent = `Image: ${file.name} | Size: ${img.width}×${img.height}px`;
                        
                        // Apply watermark with default settings
                        applyWatermark();
                    };
                    img.src = e.target.result;
                };
                
                reader.readAsDataURL(file);
            });
            
            // Apply watermark
            applyBtn.addEventListener('click', applyWatermark);
            
            // Auto-apply when settings change
            watermarkText.addEventListener('input', applyWatermark);
            fontSize.addEventListener('input', applyWatermark);
            textColor.addEventListener('input', applyWatermark);
            opacity.addEventListener('input', applyWatermark);
            position.addEventListener('change', applyWatermark);
            rotation.addEventListener('input', applyWatermark);
            
            function applyWatermark() {
                if (!originalImage) return;
                
                // Clear canvas and draw original image
                ctx.clearRect(0, 0, previewCanvas.width, previewCanvas.height);
                ctx.drawImage(originalImage, 0, 0);
                
                // Get watermark settings
                const text = watermarkText.value;
                const size = parseInt(fontSize.value);
                const color = textColor.value;
                const alpha = parseInt(opacity.value) / 100;
                const pos = position.value;
                const rot = parseInt(rotation.value);
                
                if (!text) return; // Don't apply empty watermark
                
                // Set text properties
                ctx.font = `bold ${size}px Arial`;
                ctx.fillStyle = color;
                ctx.globalAlpha = alpha;
                ctx.textAlign = 'left';
                ctx.textBaseline = 'top';
                
                // Calculate text dimensions
                const textMetrics = ctx.measureText(text);
                const textWidth = textMetrics.width;
                const textHeight = size; // Approximate height
                
                // Apply rotation if needed
                if (rot !== 0) {
                    ctx.save();
                    ctx.translate(previewCanvas.width / 2, previewCanvas.height / 2);
                    ctx.rotate(rot * Math.PI / 180);
                    ctx.translate(-previewCanvas.width / 2, -previewCanvas.height / 2);
                }
                
                // Position the watermark
                let x, y;
                const margin = 20;
                
                switch (pos) {
                    case 'top-left':
                        x = margin;
                        y = margin;
                        break;
                    case 'top-right':
                        x = previewCanvas.width - textWidth - margin;
                        y = margin;
                        ctx.textAlign = 'right';
                        break;
                    case 'bottom-left':
                        x = margin;
                        y = previewCanvas.height - textHeight - margin;
                        break;
                    case 'bottom-right':
                        x = previewCanvas.width - textWidth - margin;
                        y = previewCanvas.height - textHeight - margin;
                        ctx.textAlign = 'right';
                        break;
                    case 'center':
                        x = (previewCanvas.width - textWidth) / 2;
                        y = (previewCanvas.height - textHeight) / 2;
                        break;
                    case 'tiled':
                        // Create tiled watermark pattern
                        const spacingX = textWidth + 50;
                        const spacingY = textHeight + 30;
                        
                        for (let i = 0; i < previewCanvas.width; i += spacingX) {
                            for (let j = 0; j < previewCanvas.height; j += spacingY) {
                                ctx.fillText(text, i, j);
                            }
                        }
                        // Reset rotation if applied
                        if (rot !== 0) ctx.restore();
                        return; // Skip single watermark for tiled
                }
                
                // Draw the watermark
                ctx.fillText(text, x, y);
                
                // Reset rotation if applied
                if (rot !== 0) ctx.restore();
                
                // Store the watermarked image
                watermarkedImage = previewCanvas.toDataURL('image/png');
            }
            
            // Save image
            saveBtn.addEventListener('click', function() {
                if (!watermarkedImage) {
                    alert('Please apply a watermark first!');
                    return;
                }
                
                const link = document.createElement('a');
                link.download = 'watermarked-image.png';
                link.href = watermarkedImage;
                link.click();
            });
            
            // Reset everything
            resetBtn.addEventListener('click', function() {
                // Reset form values
                watermarkText.value = 'Your Watermark';
                fontSize.value = 36;
                fontSizeValue.textContent = '36';
                textColor.value = '#ffffff';
                opacity.value = 70;
                opacityValue.textContent = '70%';
                position.value = 'bottom-right';
                rotation.value = 0;
                rotationValue.textContent = '0°';
                
                // Reset image
                imageUpload.value = '';
                originalImage = null;
                watermarkedImage = null;
                
                // Reset canvas
                ctx.clearRect(0, 0, previewCanvas.width, previewCanvas.height);
                previewCanvas.style.display = 'none';
                canvasPlaceholder.style.display = 'block';
                imageInfo.textContent = 'No image loaded';
            });
        });
    </script>
</body>
</html>
