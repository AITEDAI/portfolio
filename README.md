<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OOO - AI 임베디드 개발자 포트폴리오</title>
    <style>
        /* 기본 스타일 */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 0 20px;
        }

        /* 헤더 스타일 */
        header {
            background: #333;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
            color: #a0a0a0;
        }

        /* 섹션 공통 스타일 */
        section {
            padding: 40px 0;
            border-bottom: 1px solid #ddd;
        }
        section h2 {
            text-align: center;
            margin-bottom: 30px;
            font-size: 2rem;
        }

        /* 기술 스택 스타일 */
        #skills .skill-category {
            margin-bottom: 20px;
        }
        #skills h3 {
            color: #333;
            border-left: 4px solid #333;
            padding-left: 10px;
        }
        #skills ul {
            list-style: none;
            padding: 0;
        }
        #skills ul li {
            background: #e2e2e2;
            display: inline-block;
            padding: 5px 15px;
            margin: 5px;
            border-radius: 5px;
            font-weight: bold;
        }
        
        /* 프로젝트 스타일 */
        .project-item {
            background: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .project-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        .project-item h3 {
            margin-top: 0;
        }
        .project-item a {
            display: inline-block;
            background: #333;
            color: #fff;
            padding: 8px 15px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .project-item a:hover {
            background: #555;
        }

        /* 연락처 및 푸터 스타일 */
        footer {
            text-align: center;
            padding: 30px;
            background: #333;
            color: #fff;
        }
        footer a {
            color: #fff;
            margin: 0 10px;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>[당신의 이름]</h1>
            <p>저전력 임베디드 환경에서 실시간 AI 모델을 구현하고 최적화하는 개발자</p>
            <p>#엣지AI #모델경량화 #NPU가속 #실시간시스템</p>
        </div>
    </header>

    <section id="skills">
        <div class="container">
            <h2>🛠️ 기술 스택</h2>
            <div class="skill-category">
                <h3>AI / Machine Learning</h3>
                <ul>
                    <li>TensorFlow Lite</li>
                    <li>PyTorch Mobile</li>
                    <li>ONNX Runtime</li>
                    <li>Model Quantization</li>
                </ul>
            </div>
            <div class="skill-category">
                <h3>Embedded Systems</h3>
                <ul>
                    <li>C / C++</li>
                    <li>Python</li>
                    <li>RTOS</li>
                    <li>NVIDIA Jetson</li>
                    <li>ARM Cortex-M</li>
                </ul>
            </div>
             <div class="skill-category">
                <h3>Tools</h3>
                <ul>
                    <li>Git</li>
                    <li>Docker</li>
                    <li>CMake</li>
                    <li>Yocto</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="projects">
        <div class="container">
            <h2>🚀 대표 프로젝트</h2>
            
            <div class="project-item">
                <h3>프로젝트 1: 엣지 디바이스를 위한 실시간 객체 탐지 시스템</h3>
                <p><strong>문제점:</strong> 네트워크 연결이 불안정한 야외 환경에서 실시간으로 객체를 탐지해야 하는 요구사항<br>
                <strong>해결책:</strong> NVIDIA Jetson Nano 보드에 경량화된 YOLOv5 모델을 포팅하여, 엣지 단에서 독립적으로 작동하는 객체 탐지 시스템을 구축했습니다.</p>
                <p><strong>주요 역할 및 기술:</strong>
                    <ul>
                        <li>YOLOv5s 모델 TensorRT 변환 및 최적화로 추론 속도 30% 향상</li>
                        <li>MIPI-CSI 카메라 드라이버 연동 및 GStreamer 파이프라인 구축</li>
                        <li>저전력 모드 구현으로 배터리 사용 시간 20% 증대</li>
                    </ul>
                </p>
                <a href="[GitHub 저장소 주소]" target="_blank">GitHub에서 코드 보기</a>
            </div>

            <div class="project-item">
                <h3>프로젝트 2: 마이크로컨트롤러 기반 음성 명령 인식 장치</h3>
                <p><strong>문제점:</strong> 기존 스마트홈 기기의 음성인식은 개인정보 유출 우려와 느린 반응 속도<br>
                <strong>해결책:</strong> ARM Cortex-M4 코어(STM32)에서 동작하는 TinyML 기반의 키워드 인식(KWS) 모델을 개발하여, 오프라인 환경에서 빠르고 안전하게 동작하는 시스템을 구현했습니다.</p>
                <p><strong>주요 역할 및 기술:</strong>
                    <ul>
                        <li>TensorFlow Lite for Microcontrollers를 사용하여 KWS 모델 포팅</li>
                        <li>PDM 마이크 인터페이스 및 오디오 전처리 알고리즘 구현</li>
                        <li>RTOS 기반의 멀티태스킹 설계(음성인식, LED 제어)</li>
                    </ul>
                </p>
                <a href="[GitHub 저장소 주소]" target="_blank">GitHub에서 코드 보기</a>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <h2>📞 연락하기</h2>
            <p>아래 채널을 통해 편하게 연락주세요.</p>
            <a href="mailto:your_email@example.com">이메일</a> |
            <a href="[GitHub 프로필 주소]" target="_blank">GitHub</a> |
            <a href="[LinkedIn 프로필 주소]" target="_blank">LinkedIn</a>
        </div>
    </footer>

</body>
</html>
