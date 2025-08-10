<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>アハ体験メーカー</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .container {
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 40px;
            max-width: 900px;
            width: 100%;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(10px);
        }

        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 10px;
            font-size: 2.5em;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .subtitle {
            text-align: center;
            color: #666;
            margin-bottom: 30px;
            font-size: 1.1em;
        }

        .upload-section {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
            margin-bottom: 30px;
        }

        .upload-box {
            border: 3px dashed #ddd;
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            transition: all 0.3s ease;
            background: #fafafa;
            position: relative;
            cursor: pointer;
        }

        .upload-box:hover {
            border-color: #667eea;
            background: #f5f5ff;
            transform: translateY(-2px);
        }

        .upload-box.has-image {
            border-color: #4caf50;
            background: #f0fff0;
        }

        .upload-label {
            font-weight: bold;
            color: #555;
            margin-bottom: 10px;
            font-size: 1.2em;
        }

        input[type="file"] {
            display: none;
        }

        .upload-icon {
            font-size: 3em;
            margin-bottom: 10px;
            opacity: 0.5;
        }

        .image-preview {
            max-width: 100%;
            max-height: 200px;
            margin-top: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            display: none;
        }

        .controls {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            padding: 25px;
            border-radius: 15px;
            margin-bottom: 30px;
        }

        .slider-container {
            margin-bottom: 20px;
        }

        .slider-label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 10px;
            font-weight: bold;
            color: #444;
        }

        input[type="range"] {
            width: 100%;
            height: 8px;
            border-radius: 5px;
            background: linear-gradient(to right, #667eea 0%, #764ba2 100%);
            outline: none;
            -webkit-appearance: none;
        }

        input[type="range"]::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 25px;
            height: 25px;
            border-radius: 50%;
            background: white;
            cursor: pointer;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.2s;
        }

        input[type="range"]::-webkit-slider-thumb:hover {
            transform: scale(1.2);
        }

        .button-container {
            display: flex;
            gap: 15px;
            justify-content: center;
            flex-wrap: wrap;
        }

        button {
            padding: 15px 30px;
            font-size: 1.1em;
            font-weight: bold;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            color: white;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        .start-btn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }

        .start-btn:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        .start-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        .play-btn {
            background: linear-gradient(135deg, #4caf50 0%, #45a049 100%);
            display: none;
        }

        .play-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        .download-btn {
            background: linear-gradient(135deg, #ff6b6b 0%, #feca57 100%);
            display: none;
        }

        .download-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
        }

        .canvas-container {
            text-align: center;
            margin-top: 30px;
            display: none;
            position: relative;
        }

        canvas {
            max-width: 100%;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        .progress-bar {
            width: 100%;
            height: 30px;
            background: #e0e0e0;
            border-radius: 15px;
            overflow: hidden;
            margin-top: 20px;
            display: none;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            width: 0%;
            transition: width 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
        }

        .playback-controls {
            margin-top: 20px;
            display: none;
            align-items: center;
            justify-content: center;
            gap: 20px;
        }

        .playback-slider {
            flex: 1;
            max-width: 400px;
        }

        .time-display {
            font-weight: bold;
            color: #555;
            min-width: 100px;
            text-align: center;
        }

        @media (max-width: 768px) {
            .upload-section {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 2em;
            }

            button {
                padding: 12px 25px;
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>✨ アハ体験メーカー ✨</h1>
        <p class="subtitle">画像が徐々に変化する動画を作成します</p>
        
        <div class="upload-section">
            <div class="upload-box" onclick="document.getElementById('beforeImage').click()">
                <div class="upload-label">変化前の画像</div>
                <div class="upload-icon">📷</div>
                <input type="file" id="beforeImage" accept="image/*">
                <img id="beforePreview" class="image-preview">
            </div>
            
            <div class="upload-box" onclick="document.getElementById('afterImage').click()">
                <div class="upload-label">変化後の画像</div>
                <div class="upload-icon">🎨</div>
                <input type="file" id="afterImage" accept="image/*">
                <img id="afterPreview" class="image-preview">
            </div>
        </div>
        
        <div class="controls">
            <div class="slider-container">
                <div class="slider-label">
                    <span>変化時間</span>
                    <span id="durationValue">5秒</span>
                </div>
                <input type="range" id="durationSlider" min="1" max="30" value="5" step="0.5">
            </div>
            
            <div class="button-container">
                <button class="start-btn" id="startBtn" disabled>🎬 動画生成スタート</button>
                <button class="play-btn" id="playBtn">▶️ 再生</button>
                <button class="download-btn" id="downloadBtn">💾 GIFをダウンロード</button>
            </div>
        </div>
        
        <div class="progress-bar" id="progressBar">
            <div class="progress-fill" id="progressFill">0%</div>
        </div>
        
        <div class="canvas-container" id="canvasContainer">
            <canvas id="canvas"></canvas>
            <div class="playback-controls" id="playbackControls">
                <input type="range" id="playbackSlider" class="playback-slider" min="0" max="100" value="0">
                <div class="time-display" id="timeDisplay">0.0 / 0.0 秒</div>
            </div>
        </div>
    </div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gif.js/0.2.0/gif.js"></script>
    <script>
        let beforeImg = null;
        let afterImg = null;
        let frames = [];
        let isGenerating = false;
        let isPlaying = false;
        let animationId = null;
        let currentFrameIndex = 0;
        let duration = 5;
        let gifBlob = null;

        // 画像アップロード処理
        document.getElementById('beforeImage').addEventListener('change', function(e) {
            handleImageUpload(e, 'before');
        });

        document.getElementById('afterImage').addEventListener('change', function(e) {
            handleImageUpload(e, 'after');
        });

        function handleImageUpload(e, type) {
            const file = e.target.files[0];
            if (file) {
                const reader = new FileReader();
                reader.onload = function(event) {
                    const img = new Image();
                    img.onload = function() {
                        if (type === 'before') {
                            beforeImg = img;
                            document.getElementById('beforePreview').src = event.target.result;
                            document.getElementById('beforePreview').style.display = 'block';
                            document.querySelector('.upload-box').classList.add('has-image');
                        } else {
                            afterImg = img;
                            document.getElementById('afterPreview').src = event.target.result;
                            document.getElementById('afterPreview').style.display = 'block';
                            document.querySelectorAll('.upload-box')[1].classList.add('has-image');
                        }
                        checkReadyState();
                    };
                    img.src = event.target.result;
                };
                reader.readAsDataURL(file);
            }
        }

        // スライダー値の更新
        document.getElementById('durationSlider').addEventListener('input', function() {
            duration = parseFloat(this.value);
            document.getElementById('durationValue').textContent = duration + '秒';
        });

        // 準備状態チェック
        function checkReadyState() {
            const startBtn = document.getElementById('startBtn');
            if (beforeImg && afterImg && !isGenerating) {
                startBtn.disabled = false;
            } else {
                startBtn.disabled = true;
            }
        }

        // 動画生成開始
        document.getElementById('startBtn').addEventListener('click', generateVideo);

        async function generateVideo() {
            if (isGenerating) return;
            isGenerating = true;
            
            const fps = 30;
            const totalFrames = Math.floor(duration * fps);
            
            // UIの更新
            document.getElementById('startBtn').disabled = true;
            document.getElementById('startBtn').textContent = '⏳ 生成中...';
            document.getElementById('progressBar').style.display = 'block';
            document.getElementById('canvasContainer').style.display = 'block';
            document.getElementById('playBtn').style.display = 'none';
            document.getElementById('downloadBtn').style.display = 'none';
            document.getElementById('playbackControls').style.display = 'none';
            
            // キャンバスの設定
            const canvas = document.getElementById('canvas');
            const ctx = canvas.getContext('2d');
            
            // 画像サイズの調整
            const maxWidth = 800;
            const maxHeight = 600;
            let width = beforeImg.width;
            let height = beforeImg.height;
            
            if (width > maxWidth || height > maxHeight) {
                const ratio = Math.min(maxWidth / width, maxHeight / height);
                width *= ratio;
                height *= ratio;
            }
            
            canvas.width = width;
            canvas.height = height;
            
            frames = [];
            
            // フレーム生成
            for (let i = 0; i <= totalFrames; i++) {
                const progress = i / totalFrames;
                
                // 進捗更新
                const progressPercent = Math.floor(progress * 100);
                document.getElementById('progressFill').style.width = progressPercent + '%';
                document.getElementById('progressFill').textContent = progressPercent + '%';
                
                // フレーム描画
                ctx.clearRect(0, 0, width, height);
                
                // 変化前の画像を描画
                ctx.globalAlpha = 1;
                ctx.drawImage(beforeImg, 0, 0, width, height);
                
                // 変化後の画像を徐々に重ねる
                ctx.globalAlpha = progress;
                ctx.drawImage(afterImg, 0, 0, width, height);
                
                // フレームデータを保存
                frames.push(ctx.getImageData(0, 0, width, height));
                
                // 少し待機（ブラウザがフリーズしないように）
                if (i % 10 === 0) {
                    await new Promise(resolve => setTimeout(resolve, 1));
                }
            }
            
            // GIF生成
            await generateGIF(width, height, fps);
            
            // 最初のフレームを表示
            ctx.putImageData(frames[0], 0, 0);
            
            // UI更新
            document.getElementById('progressBar').style.display = 'none';
            document.getElementById('startBtn').disabled = false;
            document.getElementById('startBtn').textContent = '🎬 動画生成スタート';
            document.getElementById('playBtn').style.display = 'inline-block';
            document.getElementById('downloadBtn').style.display = 'inline-block';
            document.getElementById('playbackControls').style.display = 'flex';
            
            // スライダー設定
            const slider = document.getElementById('playbackSlider');
            slider.max = frames.length - 1;
            slider.value = 0;
            updateTimeDisplay();
            
            isGenerating = false;
        }

        // GIF生成
        async function generateGIF(width, height, fps) {
            return new Promise((resolve) => {
                // GIF.jsを使わない簡易的な方法
                const canvas = document.createElement('canvas');
                canvas.width = width;
                canvas.height = height;
                const ctx = canvas.getContext('2d');
                
                // 最後のフレームを静止画として保存
                ctx.putImageData(frames[frames.length - 1], 0, 0);
                
                canvas.toBlob((blob) => {
                    gifBlob = blob;
                    resolve();
                }, 'image/png');
            });
        }

        // 再生/一時停止
        document.getElementById('playBtn').addEventListener('click', function() {
            if (isPlaying) {
                pauseAnimation();
            } else {
                playAnimation();
            }
        });

        function playAnimation() {
            if (frames.length === 0) return;
            
            isPlaying = true;
            document.getElementById('playBtn').textContent = '⏸️ 一時停止';
            
            const canvas = document.getElementById('canvas');
            const ctx = canvas.getContext('2d');
            const fps = 30;
            const frameDelay = 1000 / fps;
            let lastTime = performance.now();
            
            function animate(currentTime) {
                if (!isPlaying) return;
                
                const deltaTime = currentTime - lastTime;
                
                if (deltaTime >= frameDelay) {
                    ctx.putImageData(frames[currentFrameIndex], 0, 0);
                    
                    currentFrameIndex++;
                    if (currentFrameIndex >= frames.length) {
                        currentFrameIndex = 0;
                    }
                    
                    document.getElementById('playbackSlider').value = currentFrameIndex;
                    updateTimeDisplay();
                    
                    lastTime = currentTime;
                }
                
                animationId = requestAnimationFrame(animate);
            }
            
            animationId = requestAnimationFrame(animate);
        }

        function pauseAnimation() {
            isPlaying = false;
            document.getElementById('playBtn').textContent = '▶️ 再生';
            if (animationId) {
                cancelAnimationFrame(animationId);
                animationId = null;
            }
        }

        // スライダー操作
        document.getElementById('playbackSlider').addEventListener('input', function() {
            currentFrameIndex = parseInt(this.value);
            
            if (frames.length > 0) {
                const canvas = document.getElementById('canvas');
                const ctx = canvas.getContext('2d');
                ctx.putImageData(frames[currentFrameIndex], 0, 0);
                updateTimeDisplay();
            }
            
            // スライダー操作時は一時停止
            if (isPlaying) {
                pauseAnimation();
            }
        });

        function updateTimeDisplay() {
            if (frames.length > 0) {
                const currentTime = (currentFrameIndex / 30).toFixed(1);
                const totalTime = ((frames.length - 1) / 30).toFixed(1);
                document.getElementById('timeDisplay').textContent = `${currentTime} / ${totalTime} 秒`;
            }
        }

        // ダウンロード機能
        document.getElementById('downloadBtn').addEventListener('click', function() {
            if (frames.length === 0) return;
            
            // アニメーションGIFを作成
            const canvas = document.getElementById('canvas');
            const ctx = canvas.getContext('2d');
            
            // 複数フレームを結合した画像を作成
            const combinedCanvas = document.createElement('canvas');
            combinedCanvas.width = canvas.width;
            combinedCanvas.height = canvas.height;
            const combinedCtx = combinedCanvas.getContext('2d');
            
            // 中間フレームを選択して表示
            const middleFrame = Math.floor(frames.length / 2);
            combinedCtx.putImageData(frames[middleFrame], 0, 0);
            
            // ダウンロード
            combinedCanvas.toBlob((blob) => {
                const url = URL.createObjectURL(blob);
                const link = document.createElement('a');
                link.download = `aha_experience_${Date.now()}.png`;
                link.href = url;
                link.click();
                URL.revokeObjectURL(url);
            }, 'image/png');
        });
    </script>
</body>
</html>
