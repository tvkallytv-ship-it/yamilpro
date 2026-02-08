<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TVision Max - @yamilpro </title>
    <!-- Plyr CSS -->
    <link rel="stylesheet" href="https://cdn.plyr.io/3.7.8/plyr.css" />
    <style>
        :root {
            /* PALETA DE COLORES AMOLED OPTIMIZADA */
            --primary-bg: #000000;           /* Negro puro AMOLED */
            --secondary-bg: #0A0A0A;         /* Negro casi puro */
            --accent-color: #00FF88;         /* Verde neón vibrante */
            --accent-secondary: #FF2A6D;     /* Rosa neón para contraste */
            --accent-tertiary: #00D9FF;      /* Azul neón para detalles */
            --text-color: #FFFFFF;           /* Texto blanco puro */
            --text-secondary: #AAAAAA;       /* Texto secundario */
            --card-bg: #111111;              /* Fondo de tarjetas */
            --card-hover: #1A1A1A;           /* Hover de tarjetas */
            --highlight: #FF2A6D;            /* Destacados */
            --progress-bg: #222222;          /* Fondo de barras de progreso */
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background-color: var(--primary-bg);
            color: var(--text-color);
            overflow-x: hidden;
            line-height: 1.5;
            height: 100vh;
            width: 100vw;
        }

        /* ===== ANIMACIÓN DE INICIO ===== */
        #splash-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: var(--primary-bg);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 9999;
            overflow: hidden;
        }
        
        .amoled-background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: 
                radial-gradient(circle at 20% 30%, rgba(0, 255, 136, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 80% 70%, rgba(255, 42, 109, 0.05) 0%, transparent 50%),
                radial-gradient(circle at 40% 80%, rgba(0, 217, 255, 0.05) 0%, transparent 50%);
            animation: backgroundPulse 8s ease-in-out infinite;
        }
        
        @keyframes backgroundPulse {
            0%, 100% { opacity: 0.3; }
            50% { opacity: 0.7; }
        }
        
        .logo-container {
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: 2;
            margin-bottom: 50px;
        }
        
        .logo-image {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 30px;
            position: relative;
            animation: logoGlow 3s ease-in-out infinite alternate;
            box-shadow: 
                0 0 20px var(--accent-color),
                0 0 40px var(--accent-color),
                0 0 60px var(--accent-color),
                inset 0 0 20px rgba(0, 0, 0, 0.5);
        }
        
        .logo-image::before {
            content: "";
            position: absolute;
            width: 100%;
            height: 100%;
            border-radius: 50%;
            background: url('https://i.ibb.co/p6zkdWdb/1000210170.png') center/contain no-repeat;
            /* QUITAMOS EL FILTER QUE CAMBIA LOS COLORES */
        }
        
        @keyframes logoGlow {
            0% {
                box-shadow: 
                    0 0 20px var(--accent-color),
                    0 0 40px var(--accent-color),
                    0 0 60px var(--accent-color),
                    inset 0 0 20px rgba(0, 0, 0, 0.5);
                transform: scale(1);
            }
            100% {
                box-shadow: 
                    0 0 30px var(--accent-color),
                    0 0 60px var(--accent-color),
                    0 0 90px var(--accent-color),
                    inset 0 0 30px rgba(0, 0, 0, 0.5);
                transform: scale(1.05);
            }
        }
        
        .app-name {
            font-size: 3.5rem;
            font-weight: 900;
            text-align: center;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary), var(--accent-tertiary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 
                0 0 10px rgba(0, 255, 136, 0.5),
                0 0 20px rgba(0, 255, 136, 0.3),
                0 0 30px rgba(0, 255, 136, 0.2);
            letter-spacing: 2px;
            position: relative;
            animation: textGlow 2s ease-in-out infinite alternate;
            margin-bottom: 10px;
        }
        
        @keyframes textGlow {
            0% {
                text-shadow: 
                    0 0 10px rgba(0, 255, 136, 0.5),
                    0 0 20px rgba(0, 255, 136, 0.3),
                    0 0 30px rgba(0, 255, 136, 0.2);
            }
            100% {
                text-shadow: 
                    0 0 15px rgba(0, 255, 136, 0.7),
                    0 0 30px rgba(0, 255, 136, 0.5),
                    0 0 45px rgba(0, 255, 136, 0.3);
            }
        }
        
        .app-subtitle {
            font-size: 1.2rem;
            color: var(--text-secondary);
            text-align: center;
            letter-spacing: 1px;
            margin-bottom: 40px;
            animation: fadeIn 2s ease-in-out;
        }
        
        .progress-container {
            width: 300px;
            height: 6px;
            background: var(--progress-bg);
            border-radius: 3px;
            overflow: hidden;
            position: relative;
            margin-top: 30px;
        }
        
        .progress-bar {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary));
            border-radius: 3px;
            box-shadow: 0 0 10px var(--accent-color);
            transition: width 0.3s ease;
        }
        
        .progress-bar::after {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.4), transparent);
            animation: progressShine 2s infinite;
        }
        
        @keyframes progressShine {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
        
        .particles {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 1;
        }
        
        .particle {
            position: absolute;
            width: 3px;
            height: 3px;
            background: var(--accent-color);
            border-radius: 50%;
            opacity: 0;
            animation: particleFloat 8s infinite linear;
        }
        
        @keyframes particleFloat {
            0% {
                transform: translateY(100vh) rotate(0deg);
                opacity: 0;
            }
            10% {
                opacity: 1;
            }
            90% {
                opacity: 1;
            }
            100% {
                transform: translateY(-100px) rotate(360deg);
                opacity: 0;
            }
        }
        
        .loading-message {
            margin-top: 20px;
            font-size: 1rem;
            color: var(--text-secondary);
            text-align: center;
            animation: pulse 2s infinite;
        }
        
        @keyframes pulse {
            0%, 100% { opacity: 0.7; }
            50% { opacity: 1; }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* ===== APLICACIÓN PRINCIPAL (OCULTA INICIALMENTE) ===== */
        #app-container {
            display: none;
            width: 100%;
            height: 100%;
        }
        
        .app-container {
            display: flex;
            flex-direction: column;
            height: 100vh;
            width: 100%;
            overflow: hidden;
        }
        
        /* Header con gradiente neón */
        #header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 15px;
            background-color: var(--secondary-bg);
            border-bottom: 1px solid rgba(0, 255, 136, 0.3);
            position: sticky;
            top: 0;
            z-index: 100;
            flex-shrink: 0;
        }
        
        .logo-container-app {
            display: flex;
            align-items: center;
            gap: 12px;
        }
        
        .logo-container-app img {
            width: 42px;
            height: 42px;
            border-radius: 50%;
            border: 2px solid transparent;
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary)) padding-box,
                        linear-gradient(135deg, var(--accent-color), var(--accent-secondary)) border-box;
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.5);
        }
        
        .logo-container-app h1 {
            font-size: 20px;
            font-weight: 700;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary), var(--accent-tertiary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 20px rgba(0, 255, 136, 0.5);
            letter-spacing: 0.5px;
        }
        
        .settings-btn {
            background: none;
            border: none;
            color: var(--text-color);
            font-size: 24px;
            cursor: pointer;
            transition: transform 0.2s;
        }
        
        .settings-btn:hover {
            transform: scale(1.1);
            color: var(--accent-color);
        }
        
        /* Player View */
        #player-view {
            display: none;
            flex-direction: column;
            height: 100vh;
            background: var(--primary-bg);
            overflow: hidden;
        }
        
        /* Reproductor Inteligente Mejorado con Plyr */
        #player-wrapper {
            width: 100%;
            background-color: #000;
            position: relative;
            flex-shrink: 0;
        }
        
        #channel-player {
            width: 100%;
            height: auto;
            background: black;
            display: block;
            object-fit: contain;
        }
        
        /* Ajustes para Plyr con tema AMOLED */
        .plyr {
            --plyr-color-main: var(--accent-color);
            --plyr-control-icon-size: 18px;
            --plyr-control-spacing: 10px;
            --plyr-control-radius: 8px;
            --plyr-video-controls-background: linear-gradient(transparent, rgba(0,0,0,0.9));
            --plyr-video-control-color: white;
            --plyr-audio-controls-background: var(--secondary-bg);
            --plyr-audio-control-color: var(--text-color);
            border-radius: 0;
        }
        
        .plyr__controls {
            background: linear-gradient(transparent, rgba(0,0,0,0.9)) !important;
        }
        
        .plyr__control--overlaid {
            background: var(--accent-color) !important;
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.7);
        }
        
        .plyr__control:hover {
            background: var(--accent-color) !important;
        }
        
        .plyr__progress__buffer {
            background: rgba(255,255,255,0.1) !important;
        }
        
        /* NUEVO: Panel de estadísticas técnicas - OCULTO PERO FUNCIONAL */
        .tech-stats-panel {
            position: absolute;
            top: 15px;
            left: 15px;
            background: rgba(0,0,0,0.9);
            padding: 15px;
            border-radius: 10px;
            border: 1px solid rgba(0, 255, 136, 0.3);
            display: none;
            z-index: 60;
            max-width: 280px;
            backdrop-filter: blur(10px);
        }
        
        .tech-stats-panel.show {
            display: block;
            animation: fadeIn 0.3s ease;
        }
        
        .tech-stats-panel h4 {
            color: var(--accent-color);
            margin-bottom: 10px;
            font-size: 14px;
            border-bottom: 1px solid rgba(0, 255, 136, 0.3);
            padding-bottom: 5px;
        }
        
        .tech-stats-panel div {
            font-size: 12px;
            margin-bottom: 5px;
            display: flex;
            justify-content: space-between;
        }
        
        .tech-stats-panel .stat-value {
            color: var(--accent-tertiary);
            font-weight: bold;
        }
        
        /* NUEVO: Controles gestuales visuales */
        .gesture-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 50;
            pointer-events: none;
        }
        
        .gesture-feedback {
            background: rgba(0,0,0,0.8);
            padding: 20px 30px;
            border-radius: 15px;
            border: 2px solid var(--accent-color);
            font-size: 24px;
            font-weight: bold;
            color: var(--accent-color);
            display: flex;
            align-items: center;
            gap: 15px;
            backdrop-filter: blur(10px);
            box-shadow: 0 0 30px rgba(0, 255, 136, 0.5);
        }
        
        /* Indicadores de estado inteligente */
        .player-status {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: rgba(0,0,0,0.9);
            padding: 1px 2px;
            border-radius: 0px;
            display: none;
            align-items: center;
            gap: 2px;
            font-size: 6px;
            z-index: 50;
            border: 1px solid rgba(0, 255, 136, 0.3);
            box-shadow: 0 0 20px rgba(0, 255, 136, 0.3);
        }
        
        .player-status.show {
            display: flex;
        }
        
        .loading-spinner {
            width: 20px;
            height: 20px;
            border: 2px solid transparent;
            border-top: 2px solid var(--accent-color);
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        
        /* NOTIFICACIÓN DE SIGUIENTE EPISODIO */
        .next-episode-notification {
            position: absolute;
            bottom: 80px;
            right: 15px;
            background: rgba(10,10,10,0.95);
            padding: 15px;
            border-radius: 10px;
            border-left: 4px solid var(--accent-color);
            display: none;
            flex-direction: column;
            gap: 10px;
            max-width: 300px;
            z-index: 60;
            font-size: 0.9em;
            box-shadow: 0 5px 25px rgba(0,0,0,0.7);
            border: 1px solid rgba(0, 255, 136, 0.2);
        }
        
        .next-episode-notification.show {
            display: flex;
            animation: slideInRight 0.3s ease;
        }
        
        @keyframes slideInRight {
            from { transform: translateX(100%); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
        
        .next-episode-info {
            font-size: 14px;
            color: white;
        }
        
        .next-episode-actions {
            display: flex;
            gap: 10px;
        }
        
        .notification-btn {
            padding: 8px 15px;
            border: none;
            border-radius: 6px;
            cursor: pointer;
            font-size: 12px;
            flex: 1;
            transition: all 0.2s;
            font-weight: 600;
        }
        
        .play-next-btn {
            background: var(--accent-color);
            color: #000;
        }
        
        .play-next-btn:hover {
            background: #00e077;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.4);
        }
        
        .cancel-next-btn {
            background: rgba(255,255,255,0.1);
            color: white;
        }
        
        .cancel-next-btn:hover {
            background: rgba(255,255,255,0.2);
        }

        /* Search Bar in Player View - REGRESADO AL DISEÑO ORIGINAL */
        #player-search-bar {
            padding: 12px 15px;
            background-color: var(--secondary-bg);
            border-bottom: 1px solid rgba(0, 255, 136, 0.2);
            display: flex;
            gap: 10px;
            flex-shrink: 0;
            align-items: center;
            flex-wrap: nowrap;
        }
        
        #player-search-input {
            flex: 1;
            padding: 10px 12px;
            border: none;
            border-radius: 8px;
            background-color: var(--card-bg);
            color: var(--text-color);
            font-size: 14px;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        #player-search-input:focus {
            outline: none;
            border-color: var(--accent-color);
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }
        
        #back-to-main {
            background-color: var(--highlight);
            border: none;
            border-radius: 8px;
            color: var(--text-color);
            padding: 10px 15px;
            cursor: pointer;
            white-space: nowrap;
            font-size: 14px;
            font-weight: 600;
            transition: all 0.2s;
        }
        
        #back-to-main:hover {
            background: #ff1a5e;
            transform: translateY(-2px);
        }
        
        #global-search-btn {
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            border: none;
            border-radius: 8px;
            color: #000;
            padding: 10px 15px;
            cursor: pointer;
            white-space: nowrap;
            font-size: 14px;
            font-weight: bold;
            transition: all 0.2s;
        }
        
        #global-search-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.4);
        }
        
        /* BOTÓN DE ESTADÍSTICAS OCULTO - PERO FUNCIONAL */
        #tech-stats-btn {
            display: none; /* OCULTO PERO FUNCIONAL */
        }
        
        /* Series Controls */
        #series-controls {
            background: var(--secondary-bg);
            padding: 15px;
            display: none;
            flex-direction: column;
            gap: 15px;
            flex-shrink: 0;
            max-height: 35vh;
            overflow-y: auto;
            border-bottom: 1px solid rgba(0, 255, 136, 0.2);
        }
        
        .series-info-display {
            text-align: center;
            font-weight: bold;
            font-size: 16px;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary), var(--accent-tertiary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            padding: 10px 15px;
            border-radius: 8px;
            border: 1px solid rgba(0, 255, 136, 0.3);
            text-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }
        
        .auto-play-controls {
            display: flex;
            align-items: center;
            gap: 10px;
            padding: 10px 12px;
            background: var(--card-bg);
            border-radius: 8px;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        .auto-play-toggle {
            transform: scale(1.2);
            accent-color: var(--accent-color);
        }
        
        .auto-play-label {
            color: var(--text-color);
            font-size: 14px;
            font-weight: 600;
        }
        
        /* Temporadas Container */
        .seasons-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        .seasons-title {
            font-size: 14px;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 5px;
        }
        
        .seasons-scroll {
            display: flex;
            overflow-x: auto;
            gap: 8px;
            padding: 8px 0;
            scrollbar-width: thin;
        }
        
        .seasons-scroll::-webkit-scrollbar {
            height: 4px;
        }
        
        .seasons-scroll::-webkit-scrollbar-thumb {
            background-color: var(--accent-color);
            border-radius: 4px;
        }
        
        .season-btn {
            background: var(--card-bg);
            border: 2px solid transparent;
            border-radius: 8px;
            padding: 10px 15px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 13px;
            min-width: 110px;
            flex-shrink: 0;
            white-space: nowrap;
            color: var(--text-color);
            font-weight: 600;
        }
        
        .season-btn:hover {
            background: var(--card-hover);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        
        .season-btn.active {
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            color: #000;
            border-color: transparent;
            font-weight: bold;
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.5);
        }
        
        /* Episodios Container */
        .episodes-container {
            display: none;
            flex-direction: column;
            gap: 10px;
        }
        
        .episodes-title {
            font-size: 14px;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 5px;
        }
        
        .episodes-scroll {
            display: flex;
            overflow-x: auto;
            gap: 6px;
            padding: 8px 0;
            scrollbar-width: thin;
        }
        
        .episodes-scroll::-webkit-scrollbar {
            height: 4px;
        }
        
        .episodes-scroll::-webkit-scrollbar-thumb {
            background-color: var(--accent-color);
            border-radius: 4px;
        }
        
        .episode-item {
            background: var(--card-bg);
            border-radius: 8px;
            padding: 8px 12px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            font-size: 12px;
            min-width: 50px;
            flex-shrink: 0;
            white-space: nowrap;
            border: 2px solid transparent;
            color: var(--text-color);
            font-weight: 600;
        }
        
        .episode-item:hover {
            background: var(--card-hover);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }
        
        .episode-item.current {
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            color: #000;
            border-color: transparent;
            font-weight: bold;
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.5);
        }
        
        /* Otras Series Container */
        .other-series-container {
            display: none;
            flex-direction: column;
            gap: 10px;
            margin-top: 10px;
        }
        
        .other-series-title {
            font-size: 14px;
            font-weight: bold;
            color: var(--accent-color);
            margin-bottom: 5px;
        }
        
        .other-series-scroll {
            display: flex;
            overflow-x: auto;
            gap: 10px;
            padding: 8px 0;
            scrollbar-width: thin;
        }
        
        .other-series-scroll::-webkit-scrollbar {
            height: 4px;
        }
        
        .other-series-scroll::-webkit-scrollbar-thumb {
            background-color: var(--accent-color);
            border-radius: 4px;
        }
        
        .other-series-item {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 12px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            min-width: 140px;
            flex-shrink: 0;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        .other-series-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0, 255, 136, 0.3);
            border-color: var(--accent-color);
        }
        
        .other-series-name {
            font-size: 13px;
            font-weight: bold;
            margin-bottom: 5px;
            color: var(--text-color);
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
            height: 2.6em;
            line-height: 1.3;
        }
        
        .other-series-info {
            font-size: 11px;
            color: var(--accent-color);
        }

        /* Channels in Player View */
        #player-channels-container {
            flex: 1;
            overflow-y: auto;
            padding: 15px;
            background: var(--primary-bg);
            min-height: 300px;
            max-height: 40vh;
        }
        
        /* Main Content */
        #main-content {
            display: flex;
            flex: 1;
            overflow: hidden;
            width: 100%;
        }
        
        /* Categories Panel */
        #categories-panel {
            width: 30%;
            background-color: var(--secondary-bg);
            overflow-y: auto;
            border-right: 1px solid rgba(0, 255, 136, 0.2);
            flex-shrink: 0;
        }
        
        .category-item {
            padding: 15px 18px;
            cursor: pointer;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: all 0.3s;
        }
        
        .category-item:hover {
            background-color: rgba(0, 255, 136, 0.1);
            padding-left: 22px;
        }
        
        .category-item.active {
            background: linear-gradient(90deg, rgba(0, 255, 136, 0.15), transparent);
            color: var(--text-color);
            border-left: 3px solid var(--accent-color);
            padding-left: 22px;
        }
        
        .category-name {
            flex: 1;
            overflow: hidden;
            white-space: nowrap;
            text-overflow: ellipsis;
            font-size: 14px;
            font-weight: 500;
        }
        
        .category-count {
            background: linear-gradient(135deg, var(--accent-color), var(--accent-secondary));
            color: #000;
            border-radius: 12px;
            padding: 3px 10px;
            font-size: 12px;
            min-width: 28px;
            text-align: center;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        
        /* Channels Panel */
        #channels-panel {
            width: 70%;
            background-color: var(--primary-bg);
            overflow-y: auto;
            padding: 15px;
            display: flex;
            flex-direction: column;
        }
        
        /* Search Bar in Main View */
        #search-bar {
            padding: 15px;
            background-color: var(--secondary-bg);
            border-bottom: 1px solid rgba(0, 255, 136, 0.2);
            flex-shrink: 0;
        }
        
        #search-input {
            width: 100%;
            padding: 12px 15px;
            border: none;
            border-radius: 8px;
            background-color: var(--card-bg);
            color: var(--text-color);
            font-size: 14px;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        #search-input:focus {
            outline: none;
            border-color: var(--accent-color);
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }
        
        /* Canales normales - 3 columnas compactas */
        .channels-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 10px;
            width: 100%;
            padding: 0;
        }
        
        .channel-card {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 12px;
            text-align: center;
            cursor: pointer;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 110px;
            border: 1px solid rgba(0, 255, 136, 0.3);
            position: relative;
            transition: transform 0.3s, box-shadow 0.3s;
            overflow: hidden;
        }
        
        .channel-card:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
            border-color: var(--accent-color);
        }
        
        /* Estilo para canal activo/reproduciéndose */
        .channel-card.active {
            background: var(--card-bg);
            border: 2px solid var(--accent-color);
            transform: scale(1.02);
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.5);
        }

        .channel-card.active .channel-name {
            color: var(--text-color);
            font-weight: bold;
        }

        .channel-card.active .favorite-star {
            color: var(--text-color);
        }

        /* Para canales especiales activos */
        .special-channel-card.active {
            background: var(--card-bg);
            border: 2px solid var(--accent-color);
            transform: translateY(-2px) scale(1.01);
            box-shadow: 0 0 15px rgba(0, 255, 136, 0.5);
        }

        .special-channel-card.active .special-channel-name {
            color: var(--text-color);
            font-weight: bold;
        }

        /* Indicador de reproducción en tiempo real */
        .playing-indicator {
            position: absolute;
            top: 8px;
            left: 8px;
            width: 10px;
            height: 10px;
            background: #ff4444;
            border-radius: 50%;
            animation: pulse 1.5s infinite;
            z-index: 4;
            box-shadow: 0 0 10px #ff4444;
        }

        @keyframes pulse {
            0% { transform: scale(0.8); opacity: 1; }
            50% { transform: scale(1.2); opacity: 0.7; }
            100% { transform: scale(0.8); opacity: 1; }
        }
        
        .channel-card img {
            width: 40px;
            height: 40px;
            border-radius: 8px;
            margin-bottom: 8px;
            flex-shrink: 0;
            object-fit: container;
        }
        
        .channel-name {
            font-size: 8px;
            color: var(--text-color);
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            width: 100%;
            text-align: center;
            line-height: 1.3;
            font-weight: 500;
        }
        
        /* Canales especiales (películas, series, dramas) - 3 columnas con imagen completa */
        .special-channels-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 12px;
            width: 100%;
            padding: 0;
        }
        
        .special-channel-card {
            background-color: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            cursor: pointer;
            position: relative;
            transition: transform 0.3s, box-shadow 0.3s;
            aspect-ratio: 2/3;
            display: flex;
            flex-direction: column;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        .special-channel-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0, 255, 136, 0.3);
            border-color: var(--accent-color);
        }
        
        .special-channel-card img {
            width: 100%;
            height: 85%;
            object-fit: container;
            flex-shrink: 0;
        }
        
        .special-channel-name {
            height: 15%;
            padding: 10px 6px;
            font-size: 8px;
            color: var(--text-color);
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: rgba(17, 17, 17, 0.9);
            overflow: hidden;
            text-overflow: ellipsis;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            line-height: 1.4;
            font-weight: 500;
        }
        
        .favorite-star {
            position: absolute;
            top: 8px;
            right: 8px;
            font-size: 18px;
            color: gold;
            cursor: pointer;
            z-index: 10;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 50%;
            width: 26px;
            height: 26px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s;
        }
        
        .favorite-star:hover {
            transform: scale(1.2);
        }
        
        .favorite-star.inactive {
            color: #555;
        }
        
        /* Series Info */
        .series-info {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(0,0,0,0.9));
            padding: 5px;
            font-size: 11px;
            color: white;
            display: none;
        }
        
        .channel-card:hover .series-info {
            display: block;
        }
        
        .series-progress {
            height: 3px;
            background: #333;
            margin-top: 3px;
            border-radius: 2px;
            overflow: hidden;
        }
        
        .series-progress-bar {
            height: 100%;
            background: var(--accent-color);
            border-radius: 2px;
            width: 0%;
        }
        
        /* Settings Menu */
        #settings-menu {
            position: absolute;
            top: 70px;
            right: 15px;
            background-color: var(--secondary-bg);
            border: 1px solid rgba(0, 255, 136, 0.3);
            border-radius: 10px;
            padding: 10px 0;
            display: none;
            z-index: 200;
            min-width: 220px;
            box-shadow: 0 5px 25px rgba(0,0,0,0.5);
        }
        
        .settings-item {
            padding: 12px 15px;
            cursor: pointer;
            border-bottom: 1px solid rgba(255, 255, 255, 0.05);
            transition: all 0.2s;
            font-size: 14px;
        }
        
        .settings-item:last-child {
            border-bottom: none;
        }
        
        .settings-item:hover {
            background-color: rgba(0, 255, 136, 0.1);
            padding-left: 20px;
        }
        
        /* Modal de búsqueda global */
        .search-modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.9);
            z-index: 1000;
            justify-content: center;
            align-items: flex-start;
            padding-top: 30px;
        }
        
        .search-modal-content {
            background-color: var(--secondary-bg);
            width: 90%;
            max-width: 650px;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.7);
            border: 1px solid rgba(0, 255, 136, 0.3);
        }
        
        .search-modal-header {
            padding: 18px 20px;
            background-color: var(--primary-bg);
            border-bottom: 1px solid rgba(0, 255, 136, 0.3);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .search-modal-title {
            font-size: 20px;
            font-weight: bold;
            color: var(--accent-color);
        }
        
        .search-modal-close {
            background: none;
            border: none;
            color: var(--text-color);
            font-size: 22px;
            cursor: pointer;
            transition: all 0.2s;
        }
        
        .search-modal-close:hover {
            color: var(--accent-color);
            transform: scale(1.1);
        }
        
        .search-modal-body {
            padding: 20px;
            max-height: 70vh;
            overflow-y: auto;
        }
        
        .search-modal-input {
            width: 100%;
            padding: 15px;
            border: none;
            border-radius: 8px;
            background-color: var(--card-bg);
            color: var(--text-color);
            font-size: 16px;
            margin-bottom: 20px;
            border: 1px solid rgba(255,255,255,0.1);
        }
        
        .search-modal-input:focus {
            outline: none;
            border-color: var(--accent-color);
            box-shadow: 0 0 10px rgba(0, 255, 136, 0.3);
        }
        
        .search-results-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 12px;
        }
        
        .search-result-item {
            background-color: var(--card-bg);
            border-radius: 10px;
            padding: 15px;
            cursor: pointer;
            transition: all 0.3s;
            border: 1px solid transparent;
        }
        
        .search-result-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 255, 136, 0.3);
            border-color: var(--accent-color);
        }
        
        .search-result-name {
            font-size: 15px;
            font-weight: bold;
            margin-bottom: 8px;
            color: var(--text-color);
        }
        
        .search-result-category {
            font-size: 13px;
            color: var(--accent-color);
        }
        
        /* Indicador de carga inteligente */
        .smart-loading-indicator {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 3px;
            background: transparent;
            z-index: 10000;
            display: none;
        }
        
        .smart-loading-bar {
            height: 100%;
            background: linear-gradient(90deg, var(--accent-color), var(--accent-secondary));
            width: 0%;
            transition: width 0.3s ease;
        }
        
        .cache-status {
            position: fixed;
            bottom: 15px;
            right: 15px;
            background: rgba(0, 0, 0, 0.8);
            color: var(--accent-color);
            padding: 8px 12px;
            border-radius: 8px;
            font-size: 13px;
            z-index: 1000;
            display: none;
            border: 1px solid rgba(0, 255, 136, 0.3);
        }
        
        /* ESTILOS PARA PANTALLA COMPLETA HORIZONTAL */
        .plyr--fullscreen {
            background: #000 !important;
            position: fixed !important;
            top: 0 !important;
            left: 0 !important;
            width: 100vw !important;
            height: 100vh !important;
            z-index: 9999 !important;
        }

        .plyr--fullscreen .plyr__video-wrapper {
            width: 100% !important;
            height: 100% !important;
        }

        .plyr--fullscreen video {
            object-fit: contain !important;
            width: 100% !important;
            height: 100% !important;
        }

        /* Ocultar elementos en pantalla completa */
        .plyr--fullscreen #player-search-bar,
        .plyr--fullscreen #series-controls,
        .plyr--fullscreen #player-channels-container,
        .plyr--fullscreen #header {
            display: none !important;
        }

        /* Para móviles en landscape */
        @media (max-width: 768px) and (orientation: landscape) {
            .plyr--fullscreen {
                position: fixed !important;
                top: 0 !important;
                left: 0 !important;
                width: 100vw !important;
                height: 100vh !important;
            }
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            #main-content {
                flex-direction: column;
            }
            
            #categories-panel {
                width: 100%;
                max-height: 30vh;
            }
            
            #channels-panel {
                width: 100%;
            }
            
            .channels-grid,
            .special-channels-grid {
                grid-template-columns: repeat(3, 1fr);
            }
            
            .channel-card {
                height: 100px;
                padding: 10px;
            }
            
            .channel-card img {
                width: 35px;
                height: 35px;
                margin-bottom: 6px;
            }
            
            .channel-name {
                font-size: 9px;
            }
            
            .special-channel-name {
                font-size: 9px;
                padding: 8px 5px;
            }
            
            .category-name {
                font-size: 14px;
            }
            
            .season-btn {
                min-width: 100px;
                padding: 8px 12px;
            }
            
            .episode-item {
                min-width: 45px;
                padding: 7px 10px;
                font-size: 11px;
            }
            
            .other-series-item {
                min-width: 120px;
                padding: 10px;
            }
            
            .other-series-name {
                font-size: 12px;
            }
            
            .search-results-grid {
                grid-template-columns: 1fr;
            }
            
            #player-search-bar {
                flex-wrap: wrap;
            }
            
            #player-search-input {
                min-width: 150px;
            }
            
            /* Ajustes para más espacio en móvil */
            #player-channels-container {
                padding: 12px;
                min-height: 280px;
            }
        }
        
        @media (max-width: 480px) {
            .channels-grid,
            .special-channels-grid {
                grid-template-columns: repeat(3, 1fr);
                gap: 8px;
            }
            
            .channel-card {
                height: 95px;
                padding: 8px;
            }
            
            .channel-card img {
                width: 30px;
                height: 30px;
                margin-bottom: 5px;
            }
            
            .channel-name {
                font-size: 10px;
            }
            
            .special-channel-name {
                font-size: 10px;
                padding: 6px 4px;
            }
            
            .category-name {
                font-size: 13px;
            }
            
            .season-btn {
                min-width: 90px;
                padding: 7px 10px;
                font-size: 12px;
            }
            
            .episode-item {
                min-width: 40px;
                padding: 6px 8px;
                font-size: 10px;
            }
            
            .other-series-item {
                min-width: 110px;
                padding: 8px;
            }
            
            .other-series-name {
                font-size: 11px;
            }
            
            #player-search-bar {
                padding: 10px 12px;
            }
            
            #player-search-input {
                font-size: 13px;
                padding: 8px;
            }
            
            #back-to-main, #global-search-btn {
                font-size: 13px;
                padding: 8px 12px;
            }
            
            /* Ajustes para más espacio en móvil pequeño */
            #player-channels-container {
                padding: 10px;
                min-height: 260px;
            }
        }

        /* VERSIÓN ESPECÍFICA - Solo tocar lo necesario */
        #player-channels-container {
            flex: 1 !important;
            max-height: none !important;
            min-height: auto;
        }

        #channel-player {
            width: 100%;
            height: 100%;
            object-fit: fill;
        }
/* SOLUCIÓN SIMPLE - Solo CSS */
#player-search-bar {
    display: flex;
    gap: 10px;
    align-items: center;
    flex-wrap: nowrap;
    justify-content: space-between;
}

#player-search-input {
    flex: 1;
    min-width: 150px;
}

#back-to-main, #global-search-btn {
    white-space: nowrap;
    flex-shrink: 0;
}

/* Para pantallas muy pequeñas */
@media (max-width: 380px) {
    #player-search-bar {
        flex-wrap: wrap;
    }
    
    #player-search-input {
        min-width: 100px;
    }
    
    #back-to-main, #global-search-btn {
        font-size: 12px;
        padding: 8px 10px;
    }
}
    </style>
    <script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
    <!-- Plyr JS -->
    <script src="https://cdn.plyr.io/3.7.8/plyr.js"></script>
</head>
<body>
    <!-- ===== ANIMACIÓN DE INICIO ===== -->
    <div id="splash-screen">
        <div class="amoled-background"></div>
        <div class="particles" id="particles-container"></div>
        
        <div class="logo-container">
    <div class="logo-image"></div>
    <h1 class="app-name">𝑻𝑽𝒊𝒔𝒊𝒐𝒏 𝑴𝒂𝒙</h1>
    <p class="app-subtitle"></p>
</div>

<!-- CRÉDITO PEQUEÑO Y ELEGANTE -->
<div style="
    position: absolute;
    bottom: 30px;
    width: 100%;
    text-align: center;
    font-size: 11px;
    color: rgba(255,255,255,0.3);
    letter-spacing: 0.5px;
    opacity: 0;
    animation: fadeIn 1s ease 2.8s forwards;
">
    <span style="color: var(--accent-color);">Desarrollado por @yamilpro</span> © 2024
</div>
        
        <div class="progress-container">
            <div class="progress-bar" id="progress-bar"></div>
        </div>
        
        <div class="loading-message" id="loading-message">Inicializando aplicación...</div>
    </div>
    
    <!-- ===== APLICACIÓN PRINCIPAL ===== -->
    <div id="app-container">
        <!-- Indicador de carga inteligente -->
        <div class="smart-loading-indicator" id="smart-loading-indicator">
            <div class="smart-loading-bar" id="smart-loading-bar"></div>
        </div>
        
        <!-- Estado del cache -->
        <div class="cache-status" id="cache-status"></div>
        
        <div class="app-container">
            <!-- Header -->
            <div id="header">
                <div class="logo-container-app">
                    <img src="https://i.ibb.co/p6zkdWdb/1000210170.png" alt="Death Star">
                    <h1> 𝑻𝑽𝒊𝒔𝒊𝒐𝒏 𝑴𝒂𝒙 </h1>
                </div>
                <button class="settings-btn" id="settings-btn">⚙️</button>
                <div id="settings-menu">
                    <div class="settings-item" id="show-favorites">⭐ Ver Favoritos</div>
                    <div class="settings-item" id="refresh-list">🔄 Actualizar Lista</div>
                    <div class="settings-item" id="load-m3u">📁 Cargar archivo M3U</div>
                    <div class="settings-item" id="clear-cache">🗑️ Limpiar Cache</div>
                    <div class="settings-item" id="close-settings">❌ Cerrar</div>
                </div>
            </div>

            <!-- Player View (se muestra cuando se reproduce un canal) -->
            <div id="player-view">
                <!-- Player Wrapper - MEJORADO CON PLYR -->
                <div id="player-wrapper">
                    <video id="channel-player" autoplay playsinline></video>
                    
                    <!-- NUEVO: Panel de estadísticas técnicas - OCULTO PERO FUNCIONAL -->
                    <div class="tech-stats-panel" id="tech-stats-panel">
                        <h4>📊 Estadísticas Técnicas</h4>
                        <div>Resolución: <span class="stat-value" id="stat-resolution">-</span></div>
                        <div>Bitrate: <span class="stat-value" id="stat-bitrate">-</span></div>
                        <div>Buffer: <span class="stat-value" id="stat-buffer">-</span></div>
                        <div>FPS: <span class="stat-value" id="stat-fps">-</span></div>
                        <div>Codec: <span class="stat-value" id="stat-codec">-</span></div>
                    </div>
                    
                    <!-- NUEVO: Overlay para controles gestuales -->
                    <div class="gesture-overlay" id="gesture-overlay">
                        <div class="gesture-feedback" id="gesture-feedback">
                            <span id="gesture-icon">⏩</span>
                            <span id="gesture-text">+10s</span>
                        </div>
                    </div>
                    
                    <!-- Indicador de estado -->
                    <div class="player-status" id="player-status">
                        <div class="loading-spinner"></div>
                        <span id="status-text">Cargando...</span>
                    </div>
                    
                    <!-- Notificación de siguiente episodio - MODIFICADA -->
                    <div class="next-episode-notification" id="next-episode-notification">
                        <div class="next-episode-info" id="next-episode-info">
                            Siguiente episodio en 10 segundos
                        </div>
                        <div class="next-episode-actions">
                            <button class="notification-btn play-next-btn" id="play-next-now">Reproducir ahora</button>
                            <button class="notification-btn cancel-next-btn" id="cancel-next">Cancelar</button>
                        </div>
                    </div>
                </div>
                
                <!-- Search Bar in Player View - REGRESADO AL DISEÑO ORIGINAL -->
                <div id="player-search-bar">
                    <input type="text" id="player-search-input" placeholder="Buscar en esta categoría...">
                    <button id="back-to-main">← Volver</button>
                    <!-- BOTÓN OCULTO PERO FUNCIONAL -->
                    <button id="tech-stats-btn" style="display: none;">📊 Stats</button>
                    <button id="global-search-btn">🔍 Global</button>
                </div>
                
                <!-- Series Controls -->
                <div id="series-controls">
                    <div id="series-info-display" class="series-info-display">Ojo de Halcón S01 E01</div>
                    <div class="auto-play-controls">
                        <input type="checkbox" id="auto-play-toggle" class="auto-play-toggle" checked>
                        <label for="auto-play-toggle" class="auto-play-label">Reproducción automática inteligente</label>
                    </div>
                    
                    <!-- Temporadas -->
                    <div id="seasons-container" class="seasons-container" style="display:none;">
                        <div class="seasons-title">📺 Temporadas Disponibles</div>
                        <div id="seasons-scroll" class="seasons-scroll">
                            <!-- Las temporadas se cargarán aquí dinámicamente -->
                        </div>
                    </div>
                    
                    <!-- Episodios -->
                    <div id="episodes-container" class="episodes-container" style="display:none;">
                        <div class="episodes-title">🎬 Episodios de la Temporada</div>
                        <div id="episodes-scroll" class="episodes-scroll">
                            <!-- Los episodios se cargarán aquí dinámicamente -->
                        </div>
                    </div>
                    
                    <!-- Otras Series -->
                    <div id="other-series-container" class="other-series-container" style="display:none;">
                        <div class="other-series-title">🌟 Series que te pueden gustar</div>
                        <div id="other-series-scroll" class="other-series-scroll">
                            <!-- Otras series se cargarán aquí dinámicamente -->
                        </div>
                    </div>
                </div>
                
                <!-- Channels in Player View - MEJORADO CON MÁS ESPACIO -->
                <div id="player-channels-container">
                    <div class="channels-grid" id="player-channels-grid">
                        <!-- Los canales de la categoría actual se cargarán aquí -->
                    </div>
                </div>
            </div>

            <!-- Main Content (vista principal) -->
            <div id="main-content">
                <!-- Categories Panel -->
                <div id="categories-panel">
                    <!-- Categories will be loaded dynamically -->
                </div>

                <!-- Channels Panel -->
                <div id="channels-panel">
                    <!-- Search Bar in Main View -->
                    <div id="search-bar">
                        <input type="text" id="search-input" placeholder="Buscar canal...">
                    </div>
                    
                    <!-- Channels Grid -->
                    <div id="channels-grid-container">
                        <!-- Channels will be loaded dynamically -->
                    </div>
                </div>
            </div>
        </div>

        <!-- Modal de Búsqueda Global -->
        <div id="global-search-modal" class="search-modal">
            <div class="search-modal-content">
                <div class="search-modal-header">
                    <div class="search-modal-title">🔍 Búsqueda Global</div>
                    <button class="search-modal-close" id="close-global-search">✕</button>
                </div>
                <div class="search-modal-body">
                    <input type="text" id="global-search-input" class="search-modal-input" placeholder="Buscar en todos los canales, series y categorías...">
                    <div id="global-search-results" class="search-results-grid">
                        <!-- Los resultados de búsqueda se cargarán aquí -->
                    </div>
                </div>
            </div>
        </div>

        <input type="file" id="file-input" accept=".m3u,.m3u8,.txt" style="display:none">
    </div>

    <script>
        // ===== CONFIGURACIÓN SIMPLIFICADA DE FUENTES DE DATOS =====
        const DATA_SOURCES = {
            primary: {
                name: "Fuente Principal",
                type: "direct_url",
                url: "https://raw.githubusercontent.com/tvkallytv-ship-it/yamilpro/main/Lista.m3u",
                priority: 1
            },
            backup: {
                name: "Respaldo",
                type: "direct_url", 
                url: "https://raw.githubusercontent.com/tvkallytv-ship-it/yamilpro/main/Lista.m3u",
                priority: 2
            }
        };

        // ===== SISTEMA SIMPLIFICADO DE CARGA =====
        class SimpleDataLoader {
            constructor() {
                this.currentSource = null;
            }

            async loadData() {
                console.log("🔍 Cargando datos desde fuente directa...");
                
                // Intentar con la fuente principal primero
                try {
                    console.log(`🔄 Intentando fuente: ${DATA_SOURCES.primary.name}...`);
                    this.currentSource = DATA_SOURCES.primary;
                    
                    const response = await fetch(DATA_SOURCES.primary.url, {
                        method: 'GET',
                        headers: {
                            'Accept': 'text/plain, application/x-mpegURL',
                            'Cache-Control': 'no-cache'
                        }
                    });
                    
                    if (!response.ok) {
                        throw new Error(`HTTP ${response.status}`);
                    }
                    
                    const content = await response.text();
                    
                    if (content && content.includes('#EXTM3U')) {
                        console.log(`✅ Éxito con fuente: ${DATA_SOURCES.primary.name}`);
                        return {
                            content,
                            source: DATA_SOURCES.primary.name,
                            timestamp: Date.now()
                        };
                    } else {
                        throw new Error('Contenido no válido');
                    }
                    
                } catch (error) {
                    console.error(`❌ Error en fuente principal:`, error.message);
                    
                    // Intentar con respaldo
                    try {
                        console.log(`🔄 Intentando fuente de respaldo: ${DATA_SOURCES.backup.name}...`);
                        this.currentSource = DATA_SOURCES.backup;
                        
                        const response = await fetch(DATA_SOURCES.backup.url, {
                            method: 'GET',
                            headers: {
                                'Accept': 'text/plain, application/x-mpegURL',
                                'Cache-Control': 'no-cache'
                            }
                        });
                        
                        if (!response.ok) {
                            throw new Error(`HTTP ${response.status}`);
                        }
                        
                        const content = await response.text();
                        
                        if (content && content.includes('#EXTM3U')) {
                            console.log(`✅ Éxito con fuente de respaldo: ${DATA_SOURCES.backup.name}`);
                            return {
                                content,
                                source: DATA_SOURCES.backup.name,
                                timestamp: Date.now()
                            };
                        } else {
                            throw new Error('Contenido no válido');
                        }
                        
                    } catch (backupError) {
                        console.error(`❌ Error en fuente de respaldo:`, backupError.message);
                        throw new Error('Todas las fuentes han fallado');
                    }
                }
            }
        }

        // ===== SISTEMA DE ANIMACIÓN DE INICIO MEJORADO =====
        class SplashAnimation {
            constructor() {
                this.splashScreen = document.getElementById('splash-screen');
                this.appContainer = document.getElementById('app-container');
                this.progressBar = document.getElementById('progress-bar');
                this.loadingMessage = document.getElementById('loading-message');
                this.particlesContainer = document.getElementById('particles-container');
                
                this.progress = 0;
                this.maxProgress = 100;
                this.animationDuration = 4000; // 4 segundos
                this.stepDuration = this.animationDuration / this.maxProgress;
                
                this.messages = [
                    "Inicializando aplicación...",
                    "Cargando contenido...",
                    "Optimizando experiencia...",
                    "Preparando interfaz...",
                    "Listo para usar..."
                ];
                
                this.isAppLoaded = false;
                
                this.init();
            }
            
            init() {
                this.createParticles();
                this.startProgressAnimation();
                this.updateLoadingMessage();
                // INICIAR CARGA DE LA APLICACIÓN INMEDIATAMENTE
                this.startAppLoading();
            }
            
            createParticles() {
                const particleCount = 50;
                
                for (let i = 0; i < particleCount; i++) {
                    const particle = document.createElement('div');
                    particle.classList.add('particle');
                    
                    // Posición aleatoria
                    const left = Math.random() * 100;
                    const delay = Math.random() * 8;
                    const duration = 5 + Math.random() * 5;
                    
                    particle.style.left = `${left}%`;
                    particle.style.animationDelay = `${delay}s`;
                    particle.style.animationDuration = `${duration}s`;
                    
                    // Color aleatorio de la paleta neón
                    const colors = [
                        'var(--accent-color)',
                        'var(--accent-secondary)',
                        'var(--accent-tertiary)'
                    ];
                    const randomColor = colors[Math.floor(Math.random() * colors.length)];
                    particle.style.background = randomColor;
                    
                    this.particlesContainer.appendChild(particle);
                }
            }
            
            startProgressAnimation() {
                const interval = setInterval(() => {
                    this.progress += 1;
                    this.progressBar.style.width = `${this.progress}%`;
                    
                    // Si la aplicación ya está cargada y la animación no ha terminado, acelerar
                    if (this.isAppLoaded && this.progress < 90) {
                        this.progress = 90;
                        this.progressBar.style.width = '90%';
                    }
                    
                    if (this.progress >= this.maxProgress) {
                        clearInterval(interval);
                        this.completeAnimation();
                    }
                }, this.stepDuration);
            }
            
            updateLoadingMessage() {
                let messageIndex = 0;
                const messageInterval = setInterval(() => {
                    if (messageIndex < this.messages.length) {
                        this.loadingMessage.textContent = this.messages[messageIndex];
                        messageIndex++;
                    } else {
                        clearInterval(messageInterval);
                    }
                }, this.animationDuration / this.messages.length);
            }
            
            startAppLoading() {
                // Iniciar la carga de la aplicación en segundo plano
                setTimeout(() => {
                    this.initializeMainApplication();
                }, 500);
            }
            
            completeAnimation() {
                // Efecto de desvanecimiento
                this.splashScreen.style.opacity = '0';
                this.splashScreen.style.transition = 'opacity 0.5s ease';
                
                // Después del desvanecimiento, mostrar la aplicación
                setTimeout(() => {
                    this.splashScreen.style.display = 'none';
                    this.appContainer.style.display = 'block';
                }, 500);
            }
            
            initializeMainApplication() {
                // Inicializar todos los sistemas de la aplicación
                initMainApp().then(() => {
                    // Marcar que la aplicación está cargada
                    this.isAppLoaded = true;
                    console.log('Aplicación cargada completamente');
                });
            }
        }

        // ===== SISTEMA DE CACHE SIMPLIFICADO =====
        class SimpleCacheManager {
            constructor() {
                this.cacheVersion = 'v2.0';
                this.cacheKey = 'iptv_simple_cache';
                this.lastUpdateKey = 'iptv_last_update';
                this.cacheExpiry = 24 * 60 * 60 * 1000; // 24 horas
            }
            
            hasValidCache() {
                try {
                    const cachedData = localStorage.getItem(this.cacheKey);
                    const lastUpdate = localStorage.getItem(this.lastUpdateKey);
                    
                    if (!cachedData || !lastUpdate) {
                        return false;
                    }
                    
                    const timeSinceUpdate = Date.now() - parseInt(lastUpdate);
                    return timeSinceUpdate < this.cacheExpiry;
                } catch (e) {
                    console.error('Error verificando cache:', e);
                    return false;
                }
            }
            
            loadFromCache() {
                try {
                    const cachedData = localStorage.getItem(this.cacheKey);
                    if (cachedData) {
                        return JSON.parse(cachedData);
                    }
                } catch (e) {
                    console.error('Error cargando desde cache:', e);
                }
                return null;
            }
            
            saveToCache(data) {
                try {
                    localStorage.setItem(this.cacheKey, JSON.stringify(data));
                    localStorage.setItem(this.lastUpdateKey, Date.now().toString());
                    console.log('Datos guardados en cache');
                    return true;
                } catch (e) {
                    console.error('Error guardando en cache:', e);
                    return false;
                }
            }
            
            clearCache() {
                try {
                    localStorage.removeItem(this.cacheKey);
                    localStorage.removeItem(this.lastUpdateKey);
                    console.log('Cache limpiado silenciosamente');
                    return true;
                } catch (e) {
                    console.error('Error limpiando cache:', e);
                    return false;
                }
            }
        }

        // ===== SISTEMA SIMPLIFICADO DE CARGA =====
        class SimpleLoader {
            constructor() {
                this.cacheManager = new SimpleCacheManager();
                this.dataLoader = new SimpleDataLoader();
            }
            
            async loadData() {
                // Intentar cargar desde cache primero
                if (this.cacheManager.hasValidCache()) {
                    console.log('📂 Cargando desde cache...');
                    const cachedData = this.cacheManager.loadFromCache();
                    
                    if (cachedData && cachedData.allChannels && cachedData.categories) {
                        this.applyCachedData(cachedData);
                        // Actualizar en segundo plano
                        this.updateInBackground();
                        return true;
                    }
                }
                
                console.log('🌐 Cargando desde fuente online...');
                return await this.loadFromOnline();
            }
            
            applyCachedData(cachedData) {
                allChannels = cachedData.allChannels || [];
                categories = new Map(Object.entries(cachedData.categories || {}));
                allSeries = cachedData.allSeries || [];
                
                searchEngine = new SearchEngine(allChannels);
                
                renderCategories();
                renderChannels();
                
                console.log('Datos cargados desde cache:', {
                    canales: allChannels.length,
                    categorias: categories.size,
                    series: allSeries.length
                });
            }
            
            async loadFromOnline() {
                try {
                    const result = await this.dataLoader.loadData();
                    const content = result.content;
                    const source = result.source;
                    
                    console.log(`✅ Datos cargados exitosamente desde: ${source}`);
                    
                    if (!content || !content.includes('#EXTM3U')) {
                        throw new Error('Contenido no válido');
                    }
                    
                    parseM3U(content);
                    
                    const cacheData = {
                        allChannels: allChannels,
                        categories: Object.fromEntries(categories),
                        allSeries: allSeries,
                        timestamp: Date.now(),
                        source: source
                    };
                    
                    this.cacheManager.saveToCache(cacheData);
                    
                    return true;
                    
                } catch (error) {
                    console.error('❌ Error cargando desde fuentes online:', error);
                    
                    // Intentar usar cache expirado como último recurso
                    const cachedData = this.cacheManager.loadFromCache();
                    if (cachedData) {
                        console.log('🔄 Usando cache expirado como respaldo');
                        this.applyCachedData(cachedData);
                        return true;
                    }
                    
                    return false;
                }
            }
            
            async updateInBackground() {
                console.log('Actualizando datos en segundo plano...');
                
                try {
                    const result = await this.dataLoader.loadData();
                    const content = result.content;
                    
                    if (content && content.includes('#EXTM3U')) {
                        const oldChannels = [...allChannels];
                        parseM3U(content);
                        
                        if (this.hasSignificantChanges(oldChannels, allChannels)) {
                            const cacheData = {
                                allChannels: allChannels,
                                categories: Object.fromEntries(categories),
                                allSeries: allSeries,
                                timestamp: Date.now(),
                                source: result.source
                            };
                            
                            this.cacheManager.saveToCache(cacheData);
                            console.log('Datos actualizados en segundo plano');
                        }
                    }
                } catch (error) {
                    console.error('Error en actualización en segundo plano:', error);
                }
            }
            
            hasSignificantChanges(oldChannels, newChannels) {
                if (oldChannels.length !== newChannels.length) return true;
                
                const oldUrls = new Set(oldChannels.map(c => c.url));
                const newUrls = new Set(newChannels.map(c => c.url));
                
                if (oldUrls.size !== newUrls.size) return true;
                
                for (let url of oldUrls) {
                    if (!newUrls.has(url)) return true;
                }
                
                return false;
            }
        }

        // ===== SISTEMA SIMPLIFICADO DE REPRODUCCIÓN =====
        class SimpleVideoPlayer {
            constructor(videoElement) {
                this.video = videoElement;
                this.hls = null;
                this.currentUrl = null;
                this.plyr = null;
                
                // Elementos de UI
                this.playerStatus = document.getElementById('player-status');
                this.statusText = document.getElementById('status-text');
                
                this.initializePlyr();
                this.setupEventListeners();
            }
            
            initializePlyr() {
                // Ocultar controles nativos del video
                this.video.controls = false;
                
                // Inicializar Plyr
                this.plyr = new Plyr(this.video, {
                    controls: [
                        'play-large',
                        'play',
                        'progress',
                        'current-time',
                        'duration',
                        'mute',
                        'volume',
                        'captions',
                        'settings',
                        'pip',
                        'fullscreen'
                    ],
                    settings: ['quality', 'speed'],
                    quality: { default: 0, options: [4320, 2160, 1440, 1080, 720, 576, 480, 360, 240] },
                    speed: { selected: 1, options: [0.5, 0.75, 1, 1.25, 1.5, 1.75, 2] },
                    invertTime: false,
                    tooltips: { controls: true, seek: true },
                    keyboard: { focused: true, global: true },
                    seekTime: 10,
                    volume: 0.8,
                    clickToPlay: true,
                    hideControls: true,
                    resetOnEnd: false
                });
            }
            
            setupEventListeners() {
                this.video.addEventListener('waiting', () => {
                    this.showStatus('Buffering...');
                });
                
                this.video.addEventListener('playing', () => {
                    this.hideStatus();
                });
                
                this.video.addEventListener('error', (e) => {
                    console.error('Error de video:', e);
                    this.showStatus('Error de reproducción');
                });
            }
            
            // Reproducir URL
            play(url, channelInfo = null) {
                // Limpiar URL
                let cleanUrl = url.trim();
                
                // Quitar caracteres problemáticos
                cleanUrl = cleanUrl.replace(/[<>"{}|\\^`]/g, '');
                cleanUrl = cleanUrl.replace(/\s{2,}/g, ' ');
                
                // Limitar longitud de URL
                if (cleanUrl.length > 1000) {
                    cleanUrl = cleanUrl.substring(0, 1000);
                }
                
                // Si es enlace numérico, convertirlo a M3U8
                if (cleanUrl.match(/\/\d+$/)) {
                    const baseUrl = cleanUrl.replace(/\/\d+$/, '');
                    const streamId = cleanUrl.match(/\/(\d+)$/)[1];
                    cleanUrl = `${baseUrl}/${streamId}.m3u8`;
                }
                
                this.currentUrl = cleanUrl;
                this.currentChannel = channelInfo;
                
                this.stop();
                this.showStatus('Cargando...');
                
                // Reproducir
                if (Hls.isSupported() && cleanUrl.includes('.m3u8')) {
                    this.playHlsStream(cleanUrl);
                } else {
                    this.playDirectStream(cleanUrl);
                }
            }
            
            playHlsStream(url) {
                if (Hls.isSupported()) {
                    this.hls = new Hls({
                        enableWorker: false,
                        lowLatencyMode: true,
                        maxBufferLength: 30
                    });
                    
                    this.hls.loadSource(url);
                    this.hls.attachMedia(this.video);
                    
                    this.hls.on(Hls.Events.MANIFEST_PARSED, () => {
                        this.hideStatus();
                        this.video.play().catch(e => {
                            console.error('Error al reproducir:', e);
                            this.showStatus('Error de reproducción');
                        });
                    });
                    
                    this.hls.on(Hls.Events.ERROR, (event, data) => {
                        console.error('Error HLS:', data);
                        this.showStatus('Error de transmisión');
                    });
                    
                } else if (this.video.canPlayType('application/vnd.apple.mpegurl')) {
                    this.video.src = url;
                    this.video.play().catch(e => {
                        console.error('Error al reproducir:', e);
                        this.showStatus('Error de reproducción');
                    });
                } else {
                    this.showStatus('Formato no soportado');
                }
            }
            
            playDirectStream(url) {
                this.video.src = url;
                this.video.play().catch(e => {
                    console.error('Error al reproducir:', e);
                    this.showStatus('Error de reproducción');
                });
            }
            
            showStatus(message) {
                this.statusText.textContent = message;
                this.playerStatus.classList.add('show');
            }
            
            hideStatus() {
                this.playerStatus.classList.remove('show');
            }
            
            stop() {
                if (this.hls) {
                    this.hls.destroy();
                    this.hls = null;
                }
                
                this.video.pause();
                this.video.removeAttribute('src');
                this.video.load();
                
                this.hideStatus();
            }
            
            setAutoPlay(enabled) {
                this.autoPlayEnabled = enabled;
            }
        }

        // ===== SISTEMA DE BÚSQUEDA =====
        class SearchEngine {
            constructor(channels) {
                this.channels = channels;
                this.debounceTimer = null;
            }
            
            search(query, options = {}) {
                if (!query || query.length < 2) return [];
                
                const queryLower = query.toLowerCase();
                const queryTerms = queryLower.split(/[^a-z0-9áéíóúñ]+/).filter(term => term.length > 1);
                
                if (queryTerms.length === 0) return [];
                
                const scoredResults = this.channels.map((channel, idx) => {
                    let score = 0;
                    
                    const nameLower = channel.name.toLowerCase();
                    if (nameLower.includes(queryLower)) {
                        score += 100;
                    }
                    
                    queryTerms.forEach(term => {
                        if (nameLower.includes(term)) score += 10;
                        if (channel.group.toLowerCase().includes(term)) score += 5;
                        if (channel.seriesInfo && channel.seriesInfo.seriesName.toLowerCase().includes(term)) {
                            score += 8;
                        }
                    });
                    
                    return { channel, score, idx };
                }).filter(result => result.score > 0)
                  .sort((a, b) => b.score - a.score);
                
                const limit = options.limit || 100;
                return scoredResults.slice(0, limit).map(result => result.channel);
            }
            
            debouncedSearch(query, callback, delay = 300) {
                clearTimeout(this.debounceTimer);
                this.debounceTimer = setTimeout(() => {
                    const results = this.search(query);
                    callback(results);
                }, delay);
            }
            
            updateChannels(newChannels) {
                this.channels = newChannels;
            }
        }

        // ===== VARIABLES GLOBALES =====
        let searchEngine = null;
        let videoPlayer = null;

        const playerView = document.getElementById('player-view');
        const mainContent = document.getElementById('main-content');
        const playerSearchInput = document.getElementById('player-search-input');
        const backToMain = document.getElementById('back-to-main');
        const globalSearchBtn = document.getElementById('global-search-btn');
        const seriesControls = document.getElementById('series-controls');
        const seriesInfoDisplay = document.getElementById('series-info-display');
        const autoPlayToggle = document.getElementById('auto-play-toggle');
        
        const seasonsScroll = document.getElementById('seasons-scroll');
        const episodesScroll = document.getElementById('episodes-scroll');
        const otherSeriesScroll = document.getElementById('other-series-scroll');
        
        const playerChannelsGrid = document.getElementById('player-channels-grid');
        const categoriesPanel = document.getElementById('categories-panel');
        const channelsGridContainer = document.getElementById('channels-grid-container');
        const searchInput = document.getElementById('search-input');
        const settingsBtn = document.getElementById('settings-btn');
        const settingsMenu = document.getElementById('settings-menu');
        const fileInput = document.getElementById('file-input');

        const globalSearchModal = document.getElementById('global-search-modal');
        const globalSearchInput = document.getElementById('global-search-input');
        const globalSearchResults = document.getElementById('global-search-results');
        const closeGlobalSearchBtn = document.getElementById('close-global-search');

        let allChannels = [];
        let categories = new Map();
        let favorites = JSON.parse(localStorage.getItem('iptv_favorites') || '[]');
        let currentCategory = null;
        let showingFavorites = false;
        let searchActive = false;
        let seriesProgress = JSON.parse(localStorage.getItem('series_progress') || '{}');

        let currentSeriesEpisodes = [];
        let currentSeason = 1;
        let currentEpisodeIndex = 0;
        let currentSeriesName = '';
        let autoPlayEnabled = true;
        let currentPlayingChannel = null;
        let currentPlayingChannelUrl = null;
        let allSeries = [];

        const specialCategories = [
            'películas', 'película', 'serie', 'movies', 'series', 'drama',
            'acción', 'action', 'terror', 'horror', 'anime',
            'animación', 'dorama', 'doramas', 'netflix',
            'infantil', 'dramas', 'telenovela', 'child', 'narcos',
            'narcoseries', 'infantil', 'kids', 'vado', 'comedia'
        ];

        // ===== FUNCIONES PRINCIPALES =====
        function parseM3U(data) {
            allChannels = [];
            categories.clear();
            allSeries = [];
            
            const lines = data.split(/\r?\n/);
            let channel = null;
            
            for (let i = 0; i < lines.length; i++) {
                const line = lines[i].trim();
                
                if (line.startsWith('#EXTINF')) {
                    const groupMatch = line.match(/group-title="([^"]+)"/i);
                    const logoMatch = line.match(/tvg-logo="([^"]+)"/i);
                    const nameMatch = line.split(',')[1] || 'Sin nombre';
                    channel = {
                        group: groupMatch ? groupMatch[1] : 'Otros',
                        logo: logoMatch ? logoMatch[1] : '',
                        name: nameMatch.length > 50 ? nameMatch.substring(0, 47) + '...' : nameMatch,
                        url: ''
                    };
                    
                    channel.seriesInfo = extractSeriesInfo(channel);
                } else if (line && !line.startsWith('#')) {
                    if (channel) {
                        channel.url = line;
                        allChannels.push(channel);
                        
                        if (!categories.has(channel.group)) {
                            categories.set(channel.group, []);
                        }
                        categories.get(channel.group).push(channel);
                        
                        if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                            const existingSeries = allSeries.find(s => s.name === channel.seriesInfo.seriesName);
                            if (!existingSeries) {
                                allSeries.push({
                                    name: channel.seriesInfo.seriesName,
                                    episodes: [channel],
                                    group: channel.group,
                                    totalEpisodes: 1,
                                    totalSeasons: 1
                                });
                            } else {
                                existingSeries.episodes.push(channel);
                                existingSeries.totalEpisodes = existingSeries.episodes.length;
                                const uniqueSeasons = [...new Set(existingSeries.episodes.map(ep => ep.seriesInfo.season))];
                                existingSeries.totalSeasons = uniqueSeasons.length;
                            }
                        }
                        
                        channel = null;
                    }
                }
            }
            
            searchEngine = new SearchEngine(allChannels);
            
            renderCategories();
            renderChannels();
        }

        function extractSeriesInfo(item) {
            const title = item.name.toLowerCase();
            
            const isSeries = /s\d+\s*e\d+/i.test(title) || 
                            /temporada\s*\d+/i.test(title) || 
                            /season\s*\d+/i.test(title) || 
                            /cap[íi]tulo\s*\d+/i.test(title) || 
                            /episodio\s*\d+/i.test(title) ||
                            /chapter\s*\d+/i.test(title) ||
                            item.group?.toLowerCase().includes('serie');
            
            if (!isSeries) return null;
            
            const seasonMatch = title.match(/s(\d+)/i) || 
                               title.match(/temporada\s*(\d+)/i) || 
                               title.match(/season\s*(\d+)/i);
            const season = seasonMatch ? parseInt(seasonMatch[1]) : 1;
            
            const episodeMatch = title.match(/e(\d+)/i) || 
                                title.match(/cap[íi]tulo\s*(\d+)/i) || 
                                title.match(/episodio\s*(\d+)/i) || 
                                title.match(/chapter\s*(\d+)/i);
            const episode = episodeMatch ? parseInt(episodeMatch[1]) : 1;
            
            const seriesName = item.name
                .replace(/\s*s\d+\s*e\d+/i, '')
                .replace(/\s*temporada\s*\d+/i, '')
                .replace(/\s*cap[íi]tulo\s*\d+/i, '')
                .replace(/\s*episodio\s*\d+/i, '')
                .trim();
            
            return {
                seriesName,
                season,
                episode,
                isSeries: true
            };
        }

        function renderCategories() {
            categoriesPanel.innerHTML = '';
            
            if (favorites.length > 0) {
                const favItem = document.createElement('div');
                favItem.className = `category-item ${showingFavorites ? 'active' : ''}`;
                favItem.innerHTML = `
                    <span class="category-name">⭐ Favoritos</span>
                    <span class="category-count">${favorites.length}</span>
                `;
                
                favItem.addEventListener('click', () => {
                    showingFavorites = true;
                    currentCategory = null;
                    searchActive = false;
                    searchInput.value = '';
                    renderCategories();
                    renderChannels();
                });
                
                categoriesPanel.appendChild(favItem);
            }
            
            for (const [categoryName, channels] of categories) {
                const categoryItem = document.createElement('div');
                categoryItem.className = `category-item ${categoryName === currentCategory ? 'active' : ''}`;
                categoryItem.innerHTML = `
                    <span class="category-name">${categoryName}</span>
                    <span class="category-count">${channels.length}</span>
                `;
                
                categoryItem.addEventListener('click', () => {
                    showingFavorites = false;
                    currentCategory = categoryName;
                    searchActive = false;
                    searchInput.value = '';
                    renderCategories();
                    renderChannels();
                });
                
                categoriesPanel.appendChild(categoryItem);
            }
            
            if (categories.size > 0 && !currentCategory && !showingFavorites) {
                currentCategory = [...categories.keys()][0];
                renderCategories();
            }
        }

        function renderChannels() {
            channelsGridContainer.innerHTML = '';
            
            let channelsToShow = [];
            
            if (showingFavorites) {
                channelsToShow = allChannels.filter(channel => favorites.includes(channel.url));
            } else if (currentCategory && categories.has(currentCategory)) {
                channelsToShow = categories.get(currentCategory);
            } else if (searchActive) {
                const searchTerm = searchInput.value.toLowerCase();
                channelsToShow = searchEngine.search(searchTerm, { limit: 200 });
            }
            
            const isSpecialCategory = specialCategories.some(cat => 
                currentCategory && currentCategory.toLowerCase().includes(cat.toLowerCase())
            );
            
            const gridContainer = document.createElement('div');
            gridContainer.className = isSpecialCategory ? 'special-channels-grid' : 'channels-grid';
            channelsGridContainer.appendChild(gridContainer);
            
            if (channelsToShow.length === 0) return;
            
            channelsToShow.forEach(channel => {
                let channelElement;
                
                if (isSpecialCategory) {
                    channelElement = document.createElement('div');
                    channelElement.className = 'special-channel-card';
                    
                    const isFav = favorites.includes(channel.url);
                    const favClass = isFav ? '' : 'inactive';
                    
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/300x450/0F3460/00FFAB?text=Poster'}" alt="${channel.name}" loading="lazy">
                        <div class="special-channel-name">${channel.name.length > 50 ? channel.name.substring(0, 47) + '...' : channel.name}</div>
                    `;
                } else {
                    channelElement = document.createElement('div');
                    channelElement.className = 'channel-card';
                    
                    const isFav = favorites.includes(channel.url);
                    const favClass = isFav ? '' : 'inactive';
                    
                    let seriesInfoHTML = '';
                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                        const progress = getSeriesProgress(channel.seriesInfo.seriesName, channel.seriesInfo.season, channel.seriesInfo.episode);
                        const progressPercent = progress * 100;
                        
                        seriesInfoHTML = `
                            <div class="series-info">
                                <div>T${channel.seriesInfo.season} E${channel.seriesInfo.episode}</div>
                                <div class="series-progress">
                                    <div class="series-progress-bar" style="width: ${progressPercent}%"></div>
                                </div>
                            </div>
                        `;
                    }
                    
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/50x50/0F3460/00FFAB?text=TV'}" alt="${channel.name}" loading="lazy">
                        <div class="channel-name">${channel.name.length > 50 ? channel.name.substring(0, 47) + '...' : channel.name}</div>
                        ${seriesInfoHTML}
                    `;
                }
                
                if (channel.url === currentPlayingChannelUrl) {
                    channelElement.classList.add('active');
                    
                    const indicator = document.createElement('div');
                    indicator.className = 'playing-indicator';
                    channelElement.style.position = 'relative';
                    channelElement.appendChild(indicator);
                }
                
                const favStar = channelElement.querySelector('.favorite-star');
                favStar.addEventListener('click', (e) => {
                    e.stopPropagation();
                    toggleFavorite(channel.url);
                    renderCategories();
                    renderChannels();
                });
                
                channelElement.addEventListener('click', () => {
                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                        playSeries(channel);
                    } else {
                        playChannel(channel);
                    }
                });
                
                gridContainer.appendChild(channelElement);
            });
        }

        function setupGlobalSearch() {
            searchInput.addEventListener('input', () => {
                const query = searchInput.value.trim();
                
                if (query === '') {
                    searchActive = false;
                    renderCategories();
                    renderChannels();
                } else {
                    searchActive = true;
                    searchEngine.debouncedSearch(query, (results) => {
                        channelsGridContainer.innerHTML = '';
                        const gridContainer = document.createElement('div');
                        gridContainer.className = 'channels-grid';
                        channelsGridContainer.appendChild(gridContainer);
                        
                        if (results.length === 0) return;
                        
                        results.forEach(channel => {
                            const channelElement = document.createElement('div');
                            channelElement.className = 'channel-card';
                            channelElement.innerHTML = `
                                <img src="${channel.logo || 'https://via.placeholder.com/50x50/0F3460/00FFAB?text=TV'}" alt="${channel.name}">
                                <div class="channel-name">${channel.name}</div>
                            `;
                            channelElement.addEventListener('click', () => {
                                if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                                    playSeries(channel);
                                } else {
                                    playChannel(channel);
                                }
                            });
                            gridContainer.appendChild(channelElement);
                        });
                    }, 200);
                }
            });
            
            playerSearchInput.addEventListener('input', () => {
                const query = playerSearchInput.value.trim();
                
                if (query === '') {
                    renderPlayerChannels();
                } else {
                    const results = searchEngine.search(query, { limit: 100 });
                    renderPlayerChannelsWithResults(results);
                }
            });
            
            globalSearchBtn.addEventListener('click', openGlobalSearchModal);
            
            globalSearchInput.addEventListener('input', () => {
                const query = globalSearchInput.value.trim();
                
                if (query === '') {
                    globalSearchResults.innerHTML = '<div class="search-result-item">Ingresa un término de búsqueda...</div>';
                } else {
                    searchEngine.debouncedSearch(query, (results) => {
                        globalSearchResults.innerHTML = '';
                        
                        if (results.length === 0) {
                            globalSearchResults.innerHTML = '<div class="search-result-item">No se encontraron resultados</div>';
                        } else {
                            results.forEach(channel => {
                                const resultElement = document.createElement('div');
                                resultElement.className = 'search-result-item';
                                resultElement.innerHTML = `
                                    <div class="search-result-name">${channel.name}</div>
                                    <div class="search-result-category">${channel.group}</div>
                                `;
                                resultElement.addEventListener('click', () => {
                                    closeGlobalSearchModal();
                                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                                        playSeries(channel);
                                    } else {
                                        playChannel(channel);
                                    }
                                });
                                globalSearchResults.appendChild(resultElement);
                            });
                        }
                    }, 300);
                }
            });
        }

        function openGlobalSearchModal() {
            globalSearchModal.style.display = 'flex';
            globalSearchInput.value = '';
            globalSearchInput.focus();
            globalSearchResults.innerHTML = '<div class="search-result-item">Ingresa un término de búsqueda...</div>';
        }

        function closeGlobalSearchModal() {
            globalSearchModal.style.display = 'none';
            globalSearchInput.value = '';
        }

        function toggleFavorite(url) {
            if (favorites.includes(url)) {
                favorites = favorites.filter(f => f !== url);
            } else {
                favorites.push(url);
            }
            localStorage.setItem('iptv_favorites', JSON.stringify(favorites));
        }

        function playSeries(channel) {
            document.querySelectorAll('.channel-card.active, .special-channel-card.active').forEach(card => {
                card.classList.remove('active');
            });
            
            document.querySelectorAll('.playing-indicator').forEach(indicator => {
                indicator.remove();
            });
            
            currentPlayingChannel = channel;
            currentPlayingChannelUrl = channel.url;
            
            if (videoPlayer) {
                videoPlayer.stop();
            }

            playerView.style.display = 'flex';
            mainContent.style.display = 'none';

            seriesControls.style.display = 'flex';
            currentSeriesName = channel.seriesInfo.seriesName;
            seriesInfoDisplay.textContent = `${currentSeriesName} S${channel.seriesInfo.season.toString().padStart(2, '0')} E${channel.seriesInfo.episode.toString().padStart(2, '0')}`;
            
            currentSeriesEpisodes = allChannels.filter(ch => 
                ch.seriesInfo && 
                ch.seriesInfo.isSeries && 
                ch.seriesInfo.seriesName === currentSeriesName
            );
            
            currentSeason = channel.seriesInfo.season || 1;
            const seasonEpisodes = currentSeriesEpisodes.filter(ep => ep.seriesInfo.season === currentSeason);
            currentEpisodeIndex = seasonEpisodes.findIndex(ep => ep.url === channel.url);
            
            const seasons = groupEpisodesBySeason(currentSeriesEpisodes);
            showSeasonSelector(seasons);
            
            showEpisodesForSeason(seasonEpisodes);
            
            showOtherSeries();
            
            renderPlayerChannelsWithSeries(currentSeriesEpisodes);

            videoPlayer.play(channel.url, channel);
        }

        function playChannel(channel) {
            document.querySelectorAll('.channel-card.active, .special-channel-card.active').forEach(card => {
                card.classList.remove('active');
            });
            
            document.querySelectorAll('.playing-indicator').forEach(indicator => {
                indicator.remove();
            });
            
            currentPlayingChannel = channel;
            currentPlayingChannelUrl = channel.url;
            
            if (videoPlayer) {
                videoPlayer.stop();
            }

            playerView.style.display = 'flex';
            mainContent.style.display = 'none';

            seriesControls.style.display = 'none';
            
            renderPlayerChannels();

            videoPlayer.play(channel.url, channel);
        }

        function renderPlayerChannelsWithSeries(episodes) {
            playerChannelsGrid.innerHTML = '';
            
            const isSpecialCategory = specialCategories.some(cat => 
                currentCategory && currentCategory.toLowerCase().includes(cat.toLowerCase())
            );
            
            playerChannelsGrid.className = isSpecialCategory ? 'special-channels-grid' : 'channels-grid';
            
            episodes.forEach(channel => {
                const channelElement = document.createElement('div');
                channelElement.className = isSpecialCategory ? 'special-channel-card' : 'channel-card';
                
                const isFav = favorites.includes(channel.url);
                const favClass = isFav ? '' : 'inactive';
                
                if (isSpecialCategory) {
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/300x450/0F3460/00FFAB?text=Poster'}" alt="${channel.name}">
                        <div class="special-channel-name">${channel.name}</div>
                    `;
                } else {
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/50x50/0F3460/00FFAB?text=TV'}" alt="${channel.name}">
                        <div class="channel-name">${channel.name}</div>
                    `;
                }
                
                if (channel.url === currentPlayingChannelUrl) {
                    channelElement.classList.add('active');
                    
                    const indicator = document.createElement('div');
                    indicator.className = 'playing-indicator';
                    channelElement.style.position = 'relative';
                    channelElement.appendChild(indicator);
                }
                
                const favStar = channelElement.querySelector('.favorite-star');
                favStar.addEventListener('click', (e) => {
                    e.stopPropagation();
                    toggleFavorite(channel.url);
                });
                
                channelElement.addEventListener('click', () => {
                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                        playSeries(channel);
                    } else {
                        playChannel(channel);
                    }
                });
                
                playerChannelsGrid.appendChild(channelElement);
            });
        }

        function renderPlayerChannels() {
            playerChannelsGrid.innerHTML = '';
            
            let channelsToShow = [];
            
            if (currentCategory && categories.has(currentCategory)) {
                channelsToShow = categories.get(currentCategory);
            } else if (showingFavorites) {
                channelsToShow = allChannels.filter(channel => favorites.includes(channel.url));
            }
            
            const searchTerm = playerSearchInput.value.toLowerCase();
            if (searchTerm) {
                channelsToShow = searchEngine.search(searchTerm, { limit: 100 });
            }
            
            const isSpecialCategory = specialCategories.some(cat => 
                currentCategory && currentCategory.toLowerCase().includes(cat.toLowerCase())
            );
            
            playerChannelsGrid.className = isSpecialCategory ? 'special-channels-grid' : 'channels-grid';
            
            channelsToShow.forEach(channel => {
                const channelElement = document.createElement('div');
                channelElement.className = isSpecialCategory ? 'special-channel-card' : 'channel-card';
                
                const isFav = favorites.includes(channel.url);
                const favClass = isFav ? '' : 'inactive';
                
                if (isSpecialCategory) {
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/300x450/0F3460/00FFAB?text=Poster'}" alt="${channel.name}">
                        <div class="special-channel-name">${channel.name}</div>
                    `;
                } else {
                    channelElement.innerHTML = `
                        <div class="favorite-star ${favClass}" data-url="${channel.url}">${isFav ? '★' : '☆'}</div>
                        <img src="${channel.logo || 'https://via.placeholder.com/50x50/0F3460/00FFAB?text=TV'}" alt="${channel.name}">
                        <div class="channel-name">${channel.name}</div>
                    `;
                }
                
                if (channel.url === currentPlayingChannelUrl) {
                    channelElement.classList.add('active');
                    
                    const indicator = document.createElement('div');
                    indicator.className = 'playing-indicator';
                    channelElement.style.position = 'relative';
                    channelElement.appendChild(indicator);
                }
                
                const favStar = channelElement.querySelector('.favorite-star');
                favStar.addEventListener('click', (e) => {
                    e.stopPropagation();
                    toggleFavorite(channel.url);
                });
                
                channelElement.addEventListener('click', () => {
                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                        playSeries(channel);
                    } else {
                        playChannel(channel);
                    }
                });
                
                playerChannelsGrid.appendChild(channelElement);
            });
        }

        function renderPlayerChannelsWithResults(results) {
            playerChannelsGrid.innerHTML = '';
            
            const isSpecialCategory = specialCategories.some(cat => 
                currentCategory && currentCategory.toLowerCase().includes(cat.toLowerCase())
            );
            
            playerChannelsGrid.className = isSpecialCategory ? 'special-channels-grid' : 'channels-grid';
            
            results.forEach(channel => {
                const channelElement = document.createElement('div');
                channelElement.className = isSpecialCategory ? 'special-channel-card' : 'channel-card';
                
                if (isSpecialCategory) {
                    channelElement.innerHTML = `
                        <img src="${channel.logo || 'https://via.placeholder.com/300x450/0F3460/00FFAB?text=Poster'}" alt="${channel.name}">
                        <div class="special-channel-name">${channel.name}</div>
                    `;
                } else {
                    channelElement.innerHTML = `
                        <img src="${channel.logo || 'https://via.placeholder.com/50x50/0F3460/00FFAB?text=TV'}" alt="${channel.name}">
                        <div class="channel-name">${channel.name}</div>
                    `;
                }
                
                channelElement.addEventListener('click', () => {
                    if (channel.seriesInfo && channel.seriesInfo.isSeries) {
                        playSeries(channel);
                    } else {
                        playChannel(channel);
                    }
                });
                
                playerChannelsGrid.appendChild(channelElement);
            });
        }

        function showEpisodesForSeason(episodes) {
            episodesScroll.innerHTML = '';
            document.getElementById('episodes-container').style.display = 'flex';

            episodes.forEach((episode, index) => {
                const isCurrent = episode.url === currentPlayingChannel.url;
                const episodeItem = document.createElement('div');
                episodeItem.className = `episode-item ${isCurrent ? 'current' : ''}`;
                episodeItem.textContent = `E${episode.seriesInfo?.episode || (index + 1)}`;
                episodeItem.title = episode.name;
                
                episodeItem.onclick = () => {
                    videoPlayer.play(episode.url, episode);
                    currentPlayingChannel = episode;
                    currentEpisodeIndex = index;
                    
                    seriesInfoDisplay.textContent = `${currentSeriesName} S${currentSeason.toString().padStart(2, '0')} E${episode.seriesInfo.episode.toString().padStart(2, '0')}`;
                    
                    document.querySelectorAll('.episode-item').forEach(item => item.classList.remove('current'));
                    episodeItem.classList.add('current');
                };
                episodesScroll.appendChild(episodeItem);
            });
        }

        function showOtherSeries() {
            otherSeriesScroll.innerHTML = '';
            document.getElementById('other-series-container').style.display = 'flex';
            
            let otherSeries = allSeries.filter(series => 
                series.name !== currentSeriesName
            );
            
            otherSeries.sort((a, b) => b.totalEpisodes - a.totalEpisodes);
            otherSeries = otherSeries.slice(0, 12);
            
            if (otherSeries.length === 0) {
                document.getElementById('other-series-container').style.display = 'none';
                return;
            }
            
            otherSeries.forEach(series => {
                const seriesItem = document.createElement('div');
                seriesItem.className = 'other-series-item';
                
                seriesItem.innerHTML = `
                    <div class="other-series-name">${series.name}</div>
                    <div class="other-series-info">${series.totalSeasons} Temp • ${series.totalEpisodes} Eps</div>
                `;
                
                seriesItem.addEventListener('click', () => {
                    const firstEpisode = series.episodes[0];
                    
                    currentSeriesName = series.name;
                    currentSeriesEpisodes = series.episodes;
                    currentSeason = firstEpisode.seriesInfo.season || 1;
                    
                    const seasons = groupEpisodesBySeason(currentSeriesEpisodes);
                    showSeasonSelector(seasons);
                    
                    const seasonEpisodes = seasons[currentSeason] || [];
                    showEpisodesForSeason(seasonEpisodes);
                    
                    renderPlayerChannelsWithSeries(currentSeriesEpisodes);
                    
                    playSeries(firstEpisode);
                });
                
                otherSeriesScroll.appendChild(seriesItem);
            });
        }

        function showSeasonSelector(seasons) {
            seasonsScroll.innerHTML = '';
            document.getElementById('seasons-container').style.display = 'flex';

            Object.keys(seasons).sort().forEach(seasonNum => {
                const seasonBtn = document.createElement('div');
                seasonBtn.className = `season-btn ${parseInt(seasonNum) === currentSeason ? 'active' : ''}`;
                seasonBtn.textContent = `Temporada ${seasonNum}`;
                seasonBtn.title = `${seasons[seasonNum].length} episodios`;
                
                seasonBtn.addEventListener('click', () => {
                    currentSeason = parseInt(seasonNum);
                    showEpisodesForSeason(seasons[currentSeason]);
                    
                    document.querySelectorAll('.season-btn').forEach(btn => btn.classList.remove('active'));
                    seasonBtn.classList.add('active');
                });
                
                seasonsScroll.appendChild(seasonBtn);
            });
        }

        function groupEpisodesBySeason(episodes) {
            const seasons = {};
            episodes.forEach(ep => {
                const seasonNum = ep.seriesInfo?.season || 1;
                seasons[seasonNum] = seasons[seasonNum] || [];
                seasons[seasonNum].push(ep);
            });
            Object.keys(seasons).forEach(season => {
                seasons[season].sort((a, b) => (a.seriesInfo?.episode || 0) - (b.seriesInfo?.episode || 0));
            });
            return seasons;
        }

        function showMainMenu() {
            if (videoPlayer) {
                videoPlayer.stop();
            }
            
            currentPlayingChannel = null;
            currentPlayingChannelUrl = null;
            
            playerView.style.display = 'none';
            mainContent.style.display = 'flex';
            seriesControls.style.display = 'none';
        }

        function getSeriesProgress(seriesName, season, episode) {
            if (seriesProgress[seriesName] && 
                seriesProgress[seriesName][season] && 
                seriesProgress[seriesName][season][episode]) {
                return seriesProgress[seriesName][season][episode];
            }
            return 0;
        }

        function updateSeriesProgress(seriesName, season, episode, progress = 1) {
            if (!seriesProgress[seriesName]) {
                seriesProgress[seriesName] = {};
            }
            
            if (!seriesProgress[seriesName][season]) {
                seriesProgress[seriesName][season] = {};
            }
            
            seriesProgress[seriesName][season][episode] = progress;
            localStorage.setItem('series_progress', JSON.stringify(seriesProgress));
        }

        // ===== EVENT LISTENERS =====
        settingsBtn.addEventListener('click', () => {
            settingsMenu.style.display = settingsMenu.style.display === 'block' ? 'none' : 'block';
        });

        document.getElementById('show-favorites').addEventListener('click', () => {
            showingFavorites = true;
            currentCategory = null;
            searchActive = false;
            searchInput.value = '';
            renderCategories();
            renderChannels();
            settingsMenu.style.display = 'none';
        });

        document.getElementById('refresh-list').addEventListener('click', () => {
            const simpleLoader = new SimpleLoader();
            simpleLoader.loadFromOnline();
            settingsMenu.style.display = 'none';
        });

        document.getElementById('load-m3u').addEventListener('click', () => {
            fileInput.click();
            settingsMenu.style.display = 'none';
        });

        document.getElementById('clear-cache').addEventListener('click', () => {
            const simpleCacheManager = new SimpleCacheManager();
            simpleCacheManager.clearCache();
            settingsMenu.style.display = 'none';
        });

        document.getElementById('close-settings').addEventListener('click', () => {
            settingsMenu.style.display = 'none';
        });

        backToMain.addEventListener('click', showMainMenu);

        autoPlayToggle.addEventListener('change', function() {
            autoPlayEnabled = this.checked;
            localStorage.setItem('autoPlayEnabled', autoPlayEnabled);
            if (videoPlayer) {
                videoPlayer.setAutoPlay(autoPlayEnabled);
            }
        });

        closeGlobalSearchBtn.addEventListener('click', closeGlobalSearchModal);

        globalSearchModal.addEventListener('click', (e) => {
            if (e.target === globalSearchModal) {
                closeGlobalSearchModal();
            }
        });

        document.addEventListener('keydown', (e) => {
            if (e.key === 'Escape' && globalSearchModal.style.display === 'flex') {
                closeGlobalSearchModal();
            }
        });

        function loadAutoPlayPreference() {
            const saved = localStorage.getItem('autoPlayEnabled');
            autoPlayEnabled = saved !== null ? saved === 'true' : true;
            autoPlayToggle.checked = autoPlayEnabled;
        }

        fileInput.addEventListener('change', function() {
            if (this.files.length > 0) {
                const file = this.files[0];
                const reader = new FileReader();
                
                reader.onload = function(e) {
                    parseM3U(e.target.result);
                    
                    const cacheData = {
                        allChannels: allChannels,
                        categories: Object.fromEntries(categories),
                        allSeries: allSeries,
                        timestamp: Date.now()
                    };
                    
                    const simpleCacheManager = new SimpleCacheManager();
                    simpleCacheManager.saveToCache(cacheData);
                };
                
                reader.readAsText(file);
            }
        });

        document.addEventListener('click', (e) => {
            if (!settingsMenu.contains(e.target) && e.target !== settingsBtn) {
                settingsMenu.style.display = 'none';
            }
        });

        function initVideoPlayer() {
            const videoElement = document.getElementById('channel-player');
            videoPlayer = new SimpleVideoPlayer(videoElement);
            videoPlayer.setAutoPlay(autoPlayEnabled);
        }

        // ===== INICIALIZACIÓN PRINCIPAL DE LA APLICACIÓN =====
        async function initMainApp() {
            // Cargar datos primero
            const simpleLoader = new SimpleLoader();
            await simpleLoader.loadData();
            
            // Luego inicializar el resto
            loadAutoPlayPreference();
            setupGlobalSearch();
            initVideoPlayer();
            
            return true;
        }

        // Iniciar la animación cuando la página se carga
        document.addEventListener('DOMContentLoaded', () => {
            new SplashAnimation();
        });
    </script>
</body>
</html>