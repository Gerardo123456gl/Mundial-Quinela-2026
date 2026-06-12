
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiniela FIFA 2026 - Multidispositivo</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf-autotable/3.5.28/jspdf.plugin.autotable.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.1.1/crypto-js.min.js"></script>
    
    <!-- Firebase SDKs -->
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-app-compat.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.22.0/firebase-database-compat.js"></script>
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0a1f0a 0%, #1a3a1a 50%, #0d260d 100%);
            margin: 0;
            padding: 20px;
            min-height: 100vh;
            color: #333;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
        }

        h1 {
            text-align: center;
            color: #ffd700;
            font-size: 3em;
            margin-bottom: 30px;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
            animation: glowText 2s infinite alternate;
        }

        @keyframes glowText {
            from { text-shadow: 0 0 10px #ffd700, 0 0 20px #ffd700; }
            to { text-shadow: 0 0 20px #ffd700, 0 0 30px #ff8c00; }
        }

        .connection-status {
            position: fixed;
            top: 20px;
            right: 20px;
            padding: 10px 20px;
            border-radius: 25px;
            font-size: 12px;
            font-weight: bold;
            z-index: 9999;
            display: flex;
            align-items: center;
            gap: 8px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .status-online {
            background: linear-gradient(135deg, #28a745, #20c997);
            color: white;
        }

        .status-offline {
            background: linear-gradient(135deg, #dc3545, #c82333);
            color: white;
        }

        .status-dot {
            width: 12px;
            height: 12px;
            border-radius: 50%;
            display: inline-block;
            background: white;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { opacity: 1; transform: scale(1); }
            50% { opacity: 0.5; transform: scale(0.8); }
            100% { opacity: 1; transform: scale(1); }
        }

        .section {
            background: white;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            margin-bottom: 25px;
            animation: slideIn 0.5s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .section h2 {
            color: #1a3a1a;
            border-bottom: 3px solid #ffd700;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .flex-container {
            display: flex;
            flex-wrap: wrap;
            gap: 25px;
        }

        .column {
            flex: 1;
            min-width: 350px;
        }

        input[type="text"], 
        input[type="number"], 
        input[type="password"],
        input[type="email"],
        select {
            width: 100%;
            padding: 12px;
            margin-top: 5px;
            margin-bottom: 15px;
            border-radius: 8px;
            border: 2px solid #ddd;
            transition: all 0.3s;
            font-size: 14px;
        }

        input:focus, select:focus {
            outline: none;
            border-color: #ffd700;
            box-shadow: 0 0 0 3px rgba(255, 215, 0, 0.2);
        }

        .password-container {
            position: relative;
            width: 100%;
        }

        .password-container input {
            width: 100%;
            padding-right: 50px;
        }

        .toggle-password {
            position: absolute;
            right: 10px;
            top: 38px;
            transform: translateY(-50%);
            cursor: pointer;
            background: none;
            border: none;
            color: #666;
            font-size: 20px;
            padding: 5px;
            transition: all 0.3s;
            z-index: 10;
        }

        .toggle-password:hover {
            color: #ffd700;
            transform: translateY(-50%) scale(1.1);
        }

        button {
            padding: 12px 24px;
            margin: 5px;
            border: none;
            border-radius: 8px;
            background: linear-gradient(135deg, #1a3a1a, #2d5a2d);
            color: white;
            cursor: pointer;
            font-weight: 600;
            transition: all 0.3s;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        button:hover:not(:disabled) {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
        }

        button:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }

        .btn-gold {
            background: linear-gradient(135deg, #ffd700, #ff8c00);
            color: #1a3a1a;
            font-weight: bold;
        }

        .btn-danger {
            background: linear-gradient(135deg, #dc3545, #c82333);
        }

        .btn-success {
            background: linear-gradient(135deg, #28a745, #20c997);
        }

        .btn-info {
            background: linear-gradient(135deg, #17a2b8, #138496);
        }

        .btn-warning {
            background: linear-gradient(135deg, #ffc107, #e0a800);
            color: #333;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        th {
            background: linear-gradient(135deg, #1a3a1a, #2d5a2d);
            color: #ffd700;
            font-weight: 600;
            padding: 15px;
            font-size: 0.9em;
        }

        td {
            padding: 12px;
            text-align: center;
            border-bottom: 1px solid #eee;
        }

        tr:hover {
            background-color: #f8f9fa;
        }

        .badge {
            padding: 5px 10px;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 600;
        }

        .badge-success { background: #d4edda; color: #155724; }
        .badge-danger { background: #f8d7da; color: #721c24; }
        .badge-warning { background: #fff3cd; color: #856404; }
        .badge-info { background: #d1ecf1; color: #0c5460; }

        .alert {
            padding: 15px;
            border-radius: 8px;
            margin: 10px 0;
            animation: slideIn 0.3s ease-out;
        }

        .alert-success { background: #d4edda; border: 2px solid #28a745; color: #155724; }
        .alert-error { background: #f8d7da; border: 2px solid #dc3545; color: #721c24; }
        .alert-info { background: #d1ecf1; border: 2px solid #17a2b8; color: #0c5460; }

        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.7);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background: white;
            padding: 30px;
            border-radius: 15px;
            max-width: 600px;
            width: 90%;
            max-height: 80vh;
            overflow-y: auto;
            animation: modalSlide 0.3s ease-out;
        }

        @keyframes modalSlide {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin: 20px 0;
        }

        .stat-card {
            background: linear-gradient(135deg, #1a3a1a, #2d5a2d);
            color: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            border: 2px solid #ffd700;
        }

        .stat-number {
            font-size: 2.5em;
            font-weight: bold;
            color: #ffd700;
        }

        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            border-bottom: 2px solid #ddd;
            flex-wrap: wrap;
        }

        .tab {
            padding: 10px 20px;
            cursor: pointer;
            border: none;
            background: none;
            color: #666;
            font-weight: 600;
            transition: all 0.3s;
            border-bottom: 3px solid transparent;
        }

        .tab.active {
            color: #1a3a1a;
            border-bottom-color: #ffd700;
        }

        .password-strength {
            height: 5px;
            border-radius: 5px;
            margin-top: -10px;
            margin-bottom: 10px;
            transition: all 0.3s;
        }

        .strength-weak { background: #dc3545; width: 25%; }
        .strength-fair { background: #ffc107; width: 50%; }
        .strength-good { background: #28a745; width: 75%; }
        .strength-strong { background: #20c997; width: 100%; }

        .user-status {
            display: inline-block;
            width: 12px;
            height: 12px;
            border-radius: 50%;
            margin-right: 5px;
        }

        .status-active { background: #28a745; }
        .status-blocked { background: #dc3545; }
        .status-inactive { background: #ffc107; }

        .loading {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 3px solid #f3f3f3;
            border-top: 3px solid #ffd700;
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        @media (max-width: 768px) {
            .flex-container { flex-direction: column; }
            .column { min-width: 100%; }
            h1 { font-size: 2em; }
        }
    </style>
</head>
<body>
    <!-- Indicador de conexión -->
    <div class="connection-status status-offline" id="connectionStatus">
        <span class="status-dot"></span>
        <span id="statusText">Conectando a Firebase...</span>
    </div>

    <div class="container">
        <h1>⚽ QUINIELA FIFA 2026 🏆</h1>

        <!-- Sistema de Login/Registro -->
        <div class="section" id="loginSection">
            <h2>🔐 Acceso al Sistema</h2>
            
            <div class="flex-container">
                <!-- Iniciar Sesión -->
                <div class="column">
                    <h3>Iniciar Sesión</h3>
                    <input type="text" id="loginUsuario" placeholder="Nombre de usuario">
                    
                    <div class="password-container">
                        <input type="password" id="loginPassword" placeholder="Contraseña">
                        <button class="toggle-password" onclick="togglePassword('loginPassword', this)" title="Mostrar/ocultar contraseña">
                            👁️
                        </button>
                    </div>
                    
                    <button onclick="iniciarSesion()" class="btn-gold">Ingresar</button>
                    <button onclick="mostrarRecuperarPassword()" class="btn-warning">¿Olvidaste tu contraseña?</button>
                </div>
                
                <!-- Registrarse -->
                <div class="column">
                    <h3>Registrarse</h3>
                    <input type="text" id="registroUsuario" placeholder="Nombre de usuario (mín. 4 caracteres)">
                    <input type="email" id="registroEmail" placeholder="Email (para recuperación)">
                    
                    <div class="password-container">
                        <input type="password" id="registroPassword" placeholder="Contraseña" onkeyup="verificarFortalezaPassword()">
                        <button class="toggle-password" onclick="togglePassword('registroPassword', this)" title="Mostrar/ocultar contraseña">
                            👁️
                        </button>
                    </div>
                    <div class="password-strength" id="passwordStrength"></div>
                    
                    <div class="password-container">
                        <input type="password" id="registroPasswordConfirm" placeholder="Confirmar contraseña">
                        <button class="toggle-password" onclick="togglePassword('registroPasswordConfirm', this)" title="Mostrar/ocultar contraseña">
                            👁️
                        </button>
                    </div>
                    
                    <button onclick="registrarUsuario()" class="btn-success">Crear Cuenta</button>
                </div>
                
                <!-- Admin -->
                <div class="column">
                    <h3>Administrador</h3>
                    <input type="text" id="adminUsuario" placeholder="Usuario admin" value="admin">
                    
                    <div class="password-container">
                        <input type="password" id="adminPassword" placeholder="Contraseña admin" value="Admin2026!">
                        <button class="toggle-password" onclick="togglePassword('adminPassword', this)" title="Mostrar/ocultar contraseña">
                            👁️
                        </button>
                    </div>
                    
                    <button onclick="accesoAdmin()" class="btn-info">Panel Admin</button>
                </div>
            </div>
        </div>

        <!-- Panel Principal del Juego -->
        <div class="section" id="gameSection" style="display:none;">
            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px;">
                <h2>👋 Bienvenido, <span id="currentUser"></span></h2>
                <div>
                    <button onclick="mostrarCambiarPassword()" class="btn-warning">Cambiar Contraseña</button>
                    <button onclick="verMisPredicciones()" class="btn-info">Mis Predicciones</button>
                    <button onclick="cerrarSesion()" class="btn-danger">Cerrar Sesión</button>
                </div>
            </div>

            <div class="flex-container">
                <div class="column">
                    <h2>📅 Calendario de Partidos</h2>
                    <select id="fecha" onchange="mostrarPartidos()"></select>
                    <button onclick="mostrarPartidos()" class="btn-gold">Ver Partidos</button>
                    
                    <div style="position: relative; margin: 15px 0;">
                        <input type="text" id="buscarPartido" placeholder="🔍 Buscar equipo..." onkeyup="filtrarPartidos()">
                    </div>
                    
                    <div id="partidos" style="margin-top:10px; max-height:400px; overflow:auto;"></div>
                </div>

                <div class="column">
                    <h2>🎯 Hacer Predicción</h2>
                    <label>Partido:</label>
                    <select id="partidoParaResultado"></select>
                    
                    <div style="display: flex; gap: 10px;">
                        <div style="flex: 1;">
                            <label>Goles Local:</label>
                            <input type="number" id="golesLocal" min="0" max="20" value="0">
                        </div>
                        <div style="flex: 1;">
                            <label>Goles Visitante:</label>
                            <input type="number" id="golesVisitante" min="0" max="20" value="0">
                        </div>
                    </div>
                    
                    <div class="buttons-group" style="display: flex; gap: 10px; flex-wrap: wrap;">
                        <button onclick="guardarPrediccion()" class="btn-gold">✅ Guardar</button>
                        <button onclick="generarAleatorio()" class="btn-info">🎲 Aleatorio</button>
                        <button onclick="limpiarFormulario()" class="btn-danger">🗑️ Limpiar</button>
                    </div>

                    <div class="stats-grid" style="margin-top: 20px;">
                        <div class="stat-card">
                            <div class="stat-number" id="misPredicciones">0</div>
                            <div>Mis Predicciones</div>
                        </div>
                        <div class="stat-card">
                            <div class="stat-number" id="totalJugadores">0</div>
                            <div>Jugadores Totales</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Panel de Administrador -->
        <div class="section" id="adminSection" style="display:none; background: linear-gradient(135deg, #fff9e6, #fff3cc); border: 3px solid #ffd700;">
            <h2>👑 Panel de Administrador - Todos los Dispositivos</h2>
            
            <div class="tabs">
                <button class="tab active" onclick="cambiarTabAdmin('jugadores')">👥 Jugadores</button>
                <button class="tab" onclick="cambiarTabAdmin('predicciones')">🎯 Predicciones</button>
                <button class="tab" onclick="cambiarTabAdmin('seguridad')">🔒 Seguridad</button>
                <button class="tab" onclick="cambiarTabAdmin('estadisticas')">📊 Estadísticas</button>
            </div>

            <div id="tabJugadores">
                <h3>Gestión de Jugadores (Sincronizado en tiempo real)</h3>
                <div style="display: flex; gap: 10px; margin-bottom: 20px;">
                    <button onclick="exportarJugadoresCSV()" class="btn-success">📥 CSV</button>
                    <button onclick="exportarJugadoresPDF()" class="btn-info">📄 PDF</button>
                    <button onclick="sincronizarAhora()" class="btn-warning">🔄 Sincronizar Ahora</button>
                    <input type="text" id="buscarJugador" placeholder="🔍 Buscar jugador..." onkeyup="filtrarJugadores()" style="max-width: 300px;">
                </div>
                <div id="loadingJugadores" style="text-align: center; padding: 20px;">
                    <div class="loading"></div>
                    <p>Cargando jugadores desde la nube...</p>
                </div>
                <table id="tablaJugadores" style="display: none;">
                    <thead>
                        <tr>
                            <th>Estado</th>
                            <th>Usuario</th>
                            <th>Email</th>
                            <th>Predicciones</th>
                            <th>Último Acceso</th>
                            <th>Bloqueado</th>
                            <th>Acciones</th>
                        </tr>
                    </thead>
                    <tbody></tbody>
                </table>
            </div>

            <div id="tabPredicciones" style="display:none;">
                <h3>Todas las Predicciones</h3>
                <div style="display: flex; gap: 10px; margin-bottom: 20px;">
                    <button onclick="exportarPrediccionesCSV()" class="btn-success">📥 CSV</button>
                    <button onclick="exportarPrediccionesPDF()" class="btn-info">📄 PDF</button>
                </div>
                <table id="tablaPrediccionesAdmin">
                    <thead>
                        <tr>
                            <th>Usuario</th>
                            <th>Partido</th>
                            <th>Predicción</th>
                            <th>Grupo</th>
                            <th>Fecha</th>
                            <th>Acciones</th>
                        </tr>
                    </thead>
                    <tbody></tbody>
                </table>
            </div>

            <div id="tabSeguridad" style="display:none;">
                <h3>Gestión de Seguridad</h3>
                <div class="flex-container">
                    <div class="column">
                        <h4>🔒 Estado de Cuentas</h4>
                        <div id="listaUsuariosBloqueo" style="max-height: 400px; overflow-y: auto;"></div>
                    </div>
                    <div class="column">
                        <h4>🔑 Resetear Contraseña</h4>
                        <select id="usuarioResetPassword">
                            <option value="">Seleccionar usuario...</option>
                        </select>
                        <div class="password-container">
                            <input type="password" id="nuevaPasswordAdmin" placeholder="Nueva contraseña">
                            <button class="toggle-password" onclick="togglePassword('nuevaPasswordAdmin', this)" title="Mostrar/ocultar contraseña">
                                👁️
                            </button>
                        </div>
                        <button onclick="resetearPasswordUsuario()" class="btn-warning">Resetear Contraseña</button>
                        
                        <h4 style="margin-top: 30px;">👤 Crear Admin Secundario</h4>
                        <select id="usuarioHacerAdmin">
                            <option value="">Seleccionar usuario...</option>
                        </select>
                        <button onclick="hacerAdmin()" class="btn-info">Convertir en Admin</button>
                    </div>
                </div>
            </div>

            <div id="tabEstadisticas" style="display:none;">
                <h3>Estadísticas Generales</h3>
                <div class="stats-grid">
                    <div class="stat-card">
                        <div class="stat-number" id="adminTotalJugadores">0</div>
                        <div>Total Jugadores</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number" id="adminJugadoresActivos">0</div>
                        <div>Jugadores Activos</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number" id="adminJugadoresBloqueados">0</div>
                        <div>Jugadores Bloqueados</div>
                    </div>
                    <div class="stat-card">
                        <div class="stat-number" id="adminTotalPredicciones">0</div>
                        <div>Total Predicciones</div>
                    </div>
                </div>
                
                <div style="margin-top: 30px;">
                    <h4>Actividad Reciente</h4>
                    <div id="actividadReciente" style="max-height: 300px; overflow-y: auto;"></div>
                </div>
            </div>

            <button onclick="cerrarPanelAdmin()" class="btn-danger" style="margin-top: 20px;">Cerrar Panel Admin</button>
        </div>

        <!-- Modales -->
        <div class="modal" id="modalPredicciones">
            <div class="modal-content">
                <h2>Mis Predicciones</h2>
                <div id="contenidoModal"></div>
                <button onclick="cerrarModal()" class="btn-danger" style="margin-top: 15px;">Cerrar</button>
            </div>
        </div>

        <div class="modal" id="modalCambiarPassword">
            <div class="modal-content">
                <h2>Cambiar Contraseña</h2>
                <div class="password-container">
                    <input type="password" id="oldPassword" placeholder="Contraseña actual">
                    <button class="toggle-password" onclick="togglePassword('oldPassword', this)" title="Mostrar/ocultar contraseña">👁️</button>
                </div>
                <div class="password-container">
                    <input type="password" id="newPassword" placeholder="Nueva contraseña" onkeyup="verificarFortalezaPasswordModal()">
                    <button class="toggle-password" onclick="togglePassword('newPassword', this)" title="Mostrar/ocultar contraseña">👁️</button>
                </div>
                <div class="password-strength" id="passwordStrengthModal"></div>
                <div class="password-container">
                    <input type="password" id="confirmNewPassword" placeholder="Confirmar nueva contraseña">
                    <button class="toggle-password" onclick="togglePassword('confirmNewPassword', this)" title="Mostrar/ocultar contraseña">👁️</button>
                </div>
                <button onclick="cambiarPassword()" class="btn-gold">Cambiar Contraseña</button>
                <button onclick="cerrarModalCambiarPassword()" class="btn-danger">Cancelar</button>
            </div>
        </div>

        <div class="modal" id="modalRecuperarPassword">
            <div class="modal-content">
                <h2>Recuperar Contraseña</h2>
                <p>Ingresa tu nombre de usuario y email para recuperar tu contraseña.</p>
                <input type="text" id="recuperarUsuario" placeholder="Nombre de usuario">
                <input type="email" id="recuperarEmail" placeholder="Email registrado">
                <button onclick="recuperarPassword()" class="btn-gold">Recuperar Contraseña</button>
                <div id="resultadoRecuperacion" style="margin-top: 15px;"></div>
                <button onclick="cerrarModalRecuperarPassword()" class="btn-danger" style="margin-top: 10px;">Cancelar</button>
            </div>
        </div>
    </div>

    <script>
        // ============ CONFIGURACIÓN DE FIREBASE ============
        const firebaseConfig = {
            apiKey: "AIzaSyDRg2T1DeijjsaltBVC-0KYjmO0gLlclfI",
            authDomain: "quiniela-fifa-2026-514de.firebaseapp.com",
            databaseURL: "https://quiniela-fifa-2026-514de-default-rtdb.firebaseio.com",
            projectId: "quiniela-fifa-2026-514de",
            storageBucket: "quiniela-fifa-2026-514de.firebasestorage.app",
            messagingSenderId: "397564225467",
            appId: "1:397564225467:web:805f9c59a7e70c10f8069e"
        };

        // Inicializar Firebase
        let database = null;
        let firebaseReady = false;

        try {
            firebase.initializeApp(firebaseConfig);
            database = firebase.database();
            firebaseReady = true;
            console.log('✅ Firebase inicializado correctamente');
        } catch (error) {
            console.error('Error al inicializar Firebase:', error);
        }

        // ============ VARIABLES GLOBALES ============
        const ADMIN_CONFIG = {
            username: 'admin',
            password: 'Admin2026!',
            email: 'admin@quiniela2026.com'
        };

        let appData = {
            usuarios: {},
            configuracion: {
                maxIntentosFallidos: 5,
                bloqueoAutomatico: true,
                requiereEmail: true
            }
        };

        let currentUser = null;
        let isAdmin = false;
        let partidosFiltrados = [];

        // ============ FUNCIONES DE FIREBASE ============
        function actualizarEstadoConexion() {
            const statusDiv = document.getElementById('connectionStatus');
            const statusText = document.getElementById('statusText');
            
            if (firebaseReady) {
                statusDiv.className = 'connection-status status-online';
                statusText.textContent = '🟢 Online - Multidispositivo';
            } else {
                statusDiv.className = 'connection-status status-offline';
                statusText.textContent = '🔴 Offline - Solo local';
            }
        }

        function guardarEnFirebase() {
            if (!firebaseReady || !database) return;
            
            database.ref('usuarios').set(appData.usuarios)
                .then(() => {
                    console.log('✅ Datos guardados en Firebase');
                })
                .catch(error => {
                    console.error('Error al guardar en Firebase:', error);
                });
        }

        function cargarDesdeFirebase() {
            if (!firebaseReady || !database) return;
            
            database.ref('usuarios').once('value')
                .then((snapshot) => {
                    const usuariosFirebase = snapshot.val();
                    if (usuariosFirebase) {
                        // Combinar con datos locales
                        const datosLocales = JSON.parse(localStorage.getItem('quiniela_fifa_2026_secure') || '{}');
                        
                        // Los datos de Firebase tienen prioridad
                        appData.usuarios = {...datosLocales.usuarios, ...usuariosFirebase};
                        
                        // Guardar combinación localmente
                        localStorage.setItem('quiniela_fifa_2026_secure', JSON.stringify(appData));
                        
                        console.log('✅ Datos cargados desde Firebase:', Object.keys(appData.usuarios).length, 'usuarios');
                        actualizarEstadoConexion();
                        
                        if (isAdmin) {
                            actualizarPanelAdmin();
                        }
                    }
                })
                .catch(error => {
                    console.error('Error al cargar desde Firebase:', error);
                    actualizarEstadoConexion();
                });
        }

        function escucharCambiosFirebase() {
            if (!firebaseReady || !database) return;
            
            database.ref('usuarios').on('value', (snapshot) => {
                const usuariosFirebase = snapshot.val();
                if (usuariosFirebase) {
                    appData.usuarios = usuariosFirebase;
                    
                    // Guardar copia local
                    const datosLocales = {usuarios: usuariosFirebase, configuracion: appData.configuracion};
                    localStorage.setItem('quiniela_fifa_2026_secure', JSON.stringify(datosLocales));
                    
                    console.log('🔄 Cambios detectados en Firebase');
                    
                    // Actualizar interfaz si es necesario
                    if (isAdmin && document.getElementById('adminSection').style.display !== 'none') {
                        actualizarPanelAdmin();
                    }
                    
                    if (currentUser && !isAdmin) {
                        document.getElementById('totalJugadores').textContent = Object.keys(usuariosFirebase).length;
                        document.getElementById('misPredicciones').textContent = 
                            (usuariosFirebase[currentUser]?.predicciones || []).length;
                    }
                }
            });
        }

        function sincronizarAhora() {
            if (firebaseReady) {
                mostrarAlerta('🔄 Sincronizando con Firebase...', 'info');
                
                // Primero cargar datos de Firebase
                database.ref('usuarios').once('value')
                    .then((snapshot) => {
                        const usuariosFirebase = snapshot.val();
                        if (usuariosFirebase) {
                            appData.usuarios = usuariosFirebase;
                        }
                        
                        // Luego guardar datos locales en Firebase
                        return database.ref('usuarios').set(appData.usuarios);
                    })
                    .then(() => {
                        cargarDesdeFirebase();
                        mostrarAlerta('✅ Sincronización completada. Datos actualizados de todos los dispositivos.', 'success');
                    })
                    .catch(error => {
                        console.error('Error en sincronización:', error);
                        mostrarAlerta('Error en sincronización.', 'error');
                    });
            } else {
                mostrarAlerta('❌ Firebase no está disponible.', 'error');
            }
        }

        // ============ FUNCIONES DE SEGURIDAD ============
        function hashPassword(password) {
            return CryptoJS.SHA256(password).toString();
        }

        function verificarPassword(password, hash) {
            return hashPassword(password) === hash;
        }

        function togglePassword(inputId, button) {
            const input = document.getElementById(inputId);
            if (input.type === 'password') {
                input.type = 'text';
                button.textContent = '🙈';
            } else {
                input.type = 'password';
                button.textContent = '👁️';
            }
        }

        function verificarFortalezaPassword() {
            const password = document.getElementById('registroPassword').value;
            const strengthDiv = document.getElementById('passwordStrength');
            
            let strength = 0;
            if (password.length >= 8) strength++;
            if (password.match(/[a-z]/) && password.match(/[A-Z]/)) strength++;
            if (password.match(/[0-9]/)) strength++;
            if (password.match(/[^a-zA-Z0-9]/)) strength++;
            
            strengthDiv.className = 'password-strength';
            if (strength <= 1) strengthDiv.classList.add('strength-weak');
            else if (strength === 2) strengthDiv.classList.add('strength-fair');
            else if (strength === 3) strengthDiv.classList.add('strength-good');
            else strengthDiv.classList.add('strength-strong');
        }

        function verificarFortalezaPasswordModal() {
            const password = document.getElementById('newPassword').value;
            const strengthDiv = document.getElementById('passwordStrengthModal');
            
            let strength = 0;
            if (password.length >= 8) strength++;
            if (password.match(/[a-z]/) && password.match(/[A-Z]/)) strength++;
            if (password.match(/[0-9]/)) strength++;
            if (password.match(/[^a-zA-Z0-9]/)) strength++;
            
            strengthDiv.className = 'password-strength';
            if (strength <= 1) strengthDiv.classList.add('strength-weak');
            else if (strength === 2) strengthDiv.classList.add('strength-fair');
            else if (strength === 3) strengthDiv.classList.add('strength-good');
            else strengthDiv.classList.add('strength-strong');
        }

        function isValidEmail(email) {
            return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);
        }

        // ============ INICIALIZACIÓN ============
        function inicializarApp() {
            // Primero cargar datos locales
            cargarDatosLocales();
            cargarFechas();
            
            // Si no hay admin, crearlo
            if (!appData.usuarios[ADMIN_CONFIG.username]) {
                inicializarAdmin();
            }
            
            // Intentar cargar datos de Firebase
            if (firebaseReady) {
                cargarDesdeFirebase();
                escucharCambiosFirebase();
            }
            
            actualizarEstadoConexion();
            
            // Actualizar estado cada 30 segundos
            setInterval(actualizarEstadoConexion, 30000);
        }

        function inicializarAdmin() {
            appData.usuarios[ADMIN_CONFIG.username] = {
                passwordHash: hashPassword(ADMIN_CONFIG.password),
                email: ADMIN_CONFIG.email,
                predicciones: [],
                bloqueado: false,
                esAdmin: true,
                ultimoAcceso: new Date().toISOString(),
                intentosFallidos: 0,
                fechaRegistro: new Date().toISOString()
            };
            guardarDatos();
        }

        function cargarDatosLocales() {
            const datosGuardados = localStorage.getItem('quiniela_fifa_2026_secure');
            if (datosGuardados) {
                try {
                    appData = JSON.parse(datosGuardados);
                } catch (e) {
                    console.error('Error al cargar datos locales:', e);
                }
            }
        }

        function guardarDatos() {
            try {
                // Guardar localmente
                localStorage.setItem('quiniela_fifa_2026_secure', JSON.stringify(appData));
                
                // Guardar en Firebase si está disponible
                if (firebaseReady) {
                    guardarEnFirebase();
                }
                return true;
            } catch (e) {
                console.error('Error al guardar datos:', e);
                mostrarAlerta('Error al guardar datos.', 'error');
                return false;
            }
        }

        // ============ GESTIÓN DE USUARIOS ============
        function registrarUsuario() {
            const username = document.getElementById('registroUsuario').value.trim();
            const email = document.getElementById('registroEmail').value.trim();
            const password = document.getElementById('registroPassword').value;
            const passwordConfirm = document.getElementById('registroPasswordConfirm').value;

            if (!username || username.length < 4) {
                mostrarAlerta('El usuario debe tener al menos 4 caracteres.', 'error');
                return;
            }

            if (appData.configuracion.requiereEmail && !email) {
                mostrarAlerta('El email es requerido.', 'error');
                return;
            }

            if (!isValidEmail(email) && appData.configuracion.requiereEmail) {
                mostrarAlerta('Email no válido.', 'error');
                return;
            }

            if (password.length < 8) {
                mostrarAlerta('La contraseña debe tener al menos 8 caracteres.', 'error');
                return;
            }

            if (!password.match(/[A-Z]/) || !password.match(/[a-z]/) || !password.match(/[0-9]/)) {
                mostrarAlerta('La contraseña debe contener mayúsculas, minúsculas y números.', 'error');
                return;
            }

            if (password !== passwordConfirm) {
                mostrarAlerta('Las contraseñas no coinciden.', 'error');
                return;
            }

            if (appData.usuarios[username]) {
                mostrarAlerta('Este usuario ya existe.', 'error');
                return;
            }

            const emailExiste = Object.values(appData.usuarios).some(u => u.email === email);
            if (emailExiste && appData.configuracion.requiereEmail) {
                mostrarAlerta('Este email ya está registrado.', 'error');
                return;
            }

            appData.usuarios[username] = {
                passwordHash: hashPassword(password),
                email: email,
                predicciones: [],
                bloqueado: false,
                esAdmin: false,
                ultimoAcceso: new Date().toISOString(),
                intentosFallidos: 0,
                fechaRegistro: new Date().toISOString()
            };

            if (guardarDatos()) {
                mostrarAlerta('✅ ¡Cuenta creada exitosamente! Ya puedes iniciar sesión.', 'success');
                limpiarFormularioRegistro();
            }
        }

        function iniciarSesion() {
            const username = document.getElementById('loginUsuario').value.trim();
            const password = document.getElementById('loginPassword').value;

            if (!username || !password) {
                mostrarAlerta('Completa todos los campos.', 'error');
                return;
            }

            const usuario = appData.usuarios[username];
            
            if (!usuario) {
                mostrarAlerta('Usuario no encontrado.', 'error');
                return;
            }

            if (usuario.bloqueado) {
                mostrarAlerta('⚠️ Tu cuenta está bloqueada. Contacta al administrador.', 'error');
                return;
            }

            if (!verificarPassword(password, usuario.passwordHash)) {
                usuario.intentosFallidos++;
                
                if (appData.configuracion.bloqueoAutomatico && 
                    usuario.intentosFallidos >= appData.configuracion.maxIntentosFallidos) {
                    usuario.bloqueado = true;
                    mostrarAlerta('🔒 Cuenta bloqueada por múltiples intentos fallidos.', 'error');
                } else {
                    mostrarAlerta(`Contraseña incorrecta. Intentos restantes: ${appData.configuracion.maxIntentosFallidos - usuario.intentosFallidos}`, 'error');
                }
                
                guardarDatos();
                return;
            }

            usuario.intentosFallidos = 0;
            usuario.ultimoAcceso = new Date().toISOString();
            
            currentUser = username;
            isAdmin = usuario.esAdmin;
            
            guardarDatos();

            document.getElementById('loginSection').style.display = 'none';
            
            if (isAdmin) {
                document.getElementById('adminSection').style.display = 'block';
                document.getElementById('gameSection').style.display = 'none';
                actualizarPanelAdmin();
                mostrarAlerta('👑 Bienvenido Administrador', 'success');
            } else {
                document.getElementById('gameSection').style.display = 'block';
                document.getElementById('adminSection').style.display = 'none';
                document.getElementById('currentUser').textContent = username;
                actualizarInterfaz();
                mostrarAlerta(`✅ Bienvenido ${username}`, 'success');
            }
            
            document.getElementById('loginUsuario').value = '';
            document.getElementById('loginPassword').value = '';
        }

        function cerrarSesion() {
            currentUser = null;
            isAdmin = false;
            document.getElementById('loginSection').style.display = 'block';
            document.getElementById('gameSection').style.display = 'none';
            document.getElementById('adminSection').style.display = 'none';
        }

        function accesoAdmin() {
            const username = document.getElementById('adminUsuario').value.trim();
            const password = document.getElementById('adminPassword').value;

            if (!username || !password) {
                mostrarAlerta('Completa todos los campos.', 'error');
                return;
            }

            const usuario = appData.usuarios[username];
            
            if (!usuario || !usuario.esAdmin) {
                mostrarAlerta('Credenciales de administrador inválidas.', 'error');
                return;
            }

            if (!verificarPassword(password, usuario.passwordHash)) {
                mostrarAlerta('Contraseña incorrecta.', 'error');
                return;
            }

            currentUser = username;
            isAdmin = true;
            usuario.ultimoAcceso = new Date().toISOString();
            guardarDatos();

            document.getElementById('loginSection').style.display = 'none';
            document.getElementById('adminSection').style.display = 'block';
            document.getElementById('gameSection').style.display = 'none';
            
            actualizarPanelAdmin();
            mostrarAlerta('👑 Panel de administrador activado - Viendo datos de todos los dispositivos.', 'success');
        }

        // ============ GESTIÓN DE CONTRASEÑAS ============
        function mostrarCambiarPassword() {
            document.getElementById('modalCambiarPassword').style.display = 'flex';
        }

        function cerrarModalCambiarPassword() {
            document.getElementById('modalCambiarPassword').style.display = 'none';
            document.getElementById('oldPassword').value = '';
            document.getElementById('newPassword').value = '';
            document.getElementById('confirmNewPassword').value = '';
        }

        function cambiarPassword() {
            const oldPassword = document.getElementById('oldPassword').value;
            const newPassword = document.getElementById('newPassword').value;
            const confirmPassword = document.getElementById('confirmNewPassword').value;

            if (!oldPassword || !newPassword || !confirmPassword) {
                mostrarAlerta('Completa todos los campos.', 'error');
                return;
            }

            if (!verificarPassword(oldPassword, appData.usuarios[currentUser].passwordHash)) {
                mostrarAlerta('Contraseña actual incorrecta.', 'error');
                return;
            }

            if (newPassword.length < 8) {
                mostrarAlerta('La nueva contraseña debe tener al menos 8 caracteres.', 'error');
                return;
            }

            if (!newPassword.match(/[A-Z]/) || !newPassword.match(/[a-z]/) || !newPassword.match(/[0-9]/)) {
                mostrarAlerta('La contraseña debe contener mayúsculas, minúsculas y números.', 'error');
                return;
            }

            if (newPassword !== confirmPassword) {
                mostrarAlerta('Las contraseñas no coinciden.', 'error');
                return;
            }

            appData.usuarios[currentUser].passwordHash = hashPassword(newPassword);
            guardarDatos();
            cerrarModalCambiarPassword();
            mostrarAlerta('✅ Contraseña cambiada exitosamente.', 'success');
        }

        function mostrarRecuperarPassword() {
            document.getElementById('modalRecuperarPassword').style.display = 'flex';
        }

        function cerrarModalRecuperarPassword() {
            document.getElementById('modalRecuperarPassword').style.display = 'none';
        }

        function recuperarPassword() {
            const username = document.getElementById('recuperarUsuario').value.trim();
            const email = document.getElementById('recuperarEmail').value.trim();

            if (!username || !email) {
                mostrarAlerta('Completa todos los campos.', 'error');
                return;
            }

            const usuario = appData.usuarios[username];
            
            if (!usuario) {
                document.getElementById('resultadoRecuperacion').innerHTML = 
                    '<div class="alert alert-error">Usuario no encontrado.</div>';
                return;
            }

            if (usuario.email !== email) {
                document.getElementById('resultadoRecuperacion').innerHTML = 
                    '<div class="alert alert-error">El email no coincide con el registrado.</div>';
                return;
            }

            const tempPassword = generarPasswordTemporal();
            usuario.passwordHash = hashPassword(tempPassword);
            usuario.bloqueado = false;
            usuario.intentosFallidos = 0;
            guardarDatos();

            document.getElementById('resultadoRecuperacion').innerHTML = `
                <div class="alert alert-success">
                    <strong>✅ Contraseña recuperada!</strong><br>
                    Nueva contraseña temporal: <strong style="font-size: 1.2em;">${tempPassword}</strong><br>
                    <small>Cámbiala al iniciar sesión.</small>
                </div>
            `;
        }

        function generarPasswordTemporal() {
            const chars = 'ABCDEFGHJKLMNPQRSTUVWXYZabcdefghjkmnpqrstuvwxyz23456789!@#$';
            let password = '';
            for (let i = 0; i < 12; i++) {
                password += chars.charAt(Math.floor(Math.random() * chars.length));
            }
            return password;
        }

        // ============ FUNCIONES DE ADMINISTRADOR ============
        function resetearPasswordUsuario() {
            if (!isAdmin) return;

            const username = document.getElementById('usuarioResetPassword').value;
            const nuevaPassword = document.getElementById('nuevaPasswordAdmin').value;

            if (!username || !nuevaPassword) {
                mostrarAlerta('Selecciona un usuario y escribe una nueva contraseña.', 'error');
                return;
            }

            if (nuevaPassword.length < 8) {
                mostrarAlerta('La contraseña debe tener al menos 8 caracteres.', 'error');
                return;
            }

            if (confirm(`¿Resetear la contraseña de ${username}?`)) {
                appData.usuarios[username].passwordHash = hashPassword(nuevaPassword);
                appData.usuarios[username].bloqueado = false;
                appData.usuarios[username].intentosFallidos = 0;
                guardarDatos();
                actualizarPanelAdmin();
                document.getElementById('nuevaPasswordAdmin').value = '';
                mostrarAlerta(`✅ Contraseña de ${username} reseteada.`, 'success');
            }
        }

        function toggleBloqueoUsuario(username) {
            if (!isAdmin) return;

            const usuario = appData.usuarios[username];
            const accion = usuario.bloqueado ? 'desbloquear' : 'bloquear';
            
            if (confirm(`¿${accion} a ${username}?`)) {
                usuario.bloqueado = !usuario.bloqueado;
                if (!usuario.bloqueado) {
                    usuario.intentosFallidos = 0;
                }
                guardarDatos();
                actualizarPanelAdmin();
                mostrarAlerta(`Usuario ${username} ${accion}ado.`, 'success');
            }
        }

        function hacerAdmin() {
            if (!isAdmin) return;

            const username = document.getElementById('usuarioHacerAdmin').value;
            
            if (!username) {
                mostrarAlerta('Selecciona un usuario.', 'error');
                return;
            }

            if (confirm(`¿Convertir a ${username} en administrador?`)) {
                appData.usuarios[username].esAdmin = true;
                guardarDatos();
                actualizarPanelAdmin();
                mostrarAlerta(`${username} ahora es administrador.`, 'success');
            }
        }

        function eliminarJugador(username) {
            if (!isAdmin) return;
            
            if (username === ADMIN_CONFIG.username) {
                mostrarAlerta('No puedes eliminar al administrador principal.', 'error');
                return;
            }

            if (confirm(`¿Eliminar permanentemente a ${username}?`)) {
                delete appData.usuarios[username];
                guardarDatos();
                actualizarPanelAdmin();
                mostrarAlerta(`Usuario ${username} eliminado.`, 'success');
            }
        }

        // ============ ACTUALIZACIÓN DE INTERFAZ ADMIN ============
        function actualizarPanelAdmin() {
            if (!isAdmin) return;
            
            document.getElementById('loadingJugadores').style.display = 'none';
            document.getElementById('tablaJugadores').style.display = 'table';
            
            actualizarTabJugadores();
            actualizarTabPredicciones();
            actualizarTabSeguridad();
            actualizarTabEstadisticas();
        }

        function actualizarTabJugadores() {
            const tbody = document.querySelector('#tablaJugadores tbody');
            tbody.innerHTML = '';

            Object.keys(appData.usuarios).forEach(username => {
                const user = appData.usuarios[username];
                const estadoClass = user.bloqueado ? 'status-blocked' : 
                                   (new Date(user.ultimoAcceso).getTime() > Date.now() - 7*24*60*60*1000 ? 'status-active' : 'status-inactive');
                const estadoTexto = user.bloqueado ? 'Bloqueado' : 
                                   (new Date(user.ultimoAcceso).getTime() > Date.now() - 7*24*60*60*1000 ? 'Activo' : 'Inactivo');
                
                const fila = document.createElement('tr');
                fila.innerHTML = `
                    <td><span class="user-status ${estadoClass}"></span>${estadoTexto}</td>
                    <td><strong>${username}</strong>${user.esAdmin ? ' 👑' : ''}</td>
                    <td>${user.email || 'N/A'}</td>
                    <td>${user.predicciones.length}</td>
                    <td>${new Date(user.ultimoAcceso).toLocaleString()}</td>
                    <td><span class="badge ${user.bloqueado ? 'badge-danger' : 'badge-success'}">${user.bloqueado ? 'SÍ' : 'NO'}</span></td>
                    <td>
                        <button onclick="verPrediccionesDe('${username}')" class="btn-info" style="padding:5px 10px; font-size:12px;">Ver</button>
                        <button onclick="toggleBloqueoUsuario('${username}')" class="${user.bloqueado ? 'btn-success' : 'btn-danger'}" style="padding:5px 10px; font-size:12px;">
                            ${user.bloqueado ? 'Desbloquear' : 'Bloquear'}
                        </button>
                        ${username !== ADMIN_CONFIG.username ? 
                            `<button onclick="eliminarJugador('${username}')" class="btn-danger" style="padding:5px 10px; font-size:12px;">Eliminar</button>` : 
                            ''}
                    </td>
                `;
                tbody.appendChild(fila);
            });
        }

        function actualizarTabPredicciones() {
            const tbody = document.querySelector('#tablaPrediccionesAdmin tbody');
            tbody.innerHTML = '';

            Object.keys(appData.usuarios).forEach(username => {
                appData.usuarios[username].predicciones.forEach((p, index) => {
                    const fila = document.createElement('tr');
                    fila.innerHTML = `
                        <td>${username}</td>
                        <td>${p.partido}</td>
                        <td><strong>${p.resultado}</strong></td>
                        <td><span class="badge badge-info">${p.grupo}</span></td>
                        <td>${new Date(p.fecha).toLocaleDateString()}</td>
                        <td>
                            <button onclick="eliminarPrediccionAdmin('${username}', ${index})" class="btn-danger" style="padding:5px 10px;">Eliminar</button>
                        </td>
                    `;
                    tbody.appendChild(fila);
                });
            });
        }

        function actualizarTabSeguridad() {
            const div = document.getElementById('listaUsuariosBloqueo');
            div.innerHTML = '<table><tr><th>Usuario</th><th>Estado</th><th>Intentos Fallidos</th><th>Acción</th></tr>';
            
            Object.keys(appData.usuarios).forEach(username => {
                if (username === ADMIN_CONFIG.username) return;
                const user = appData.usuarios[username];
                div.innerHTML += `
                    <tr>
                        <td>${username}</td>
                        <td><span class="badge ${user.bloqueado ? 'badge-danger' : 'badge-success'}">${user.bloqueado ? 'Bloqueado' : 'Activo'}</span></td>
                        <td>${user.intentosFallidos}</td>
                        <td>
                            <button onclick="toggleBloqueoUsuario('${username}')" class="${user.bloqueado ? 'btn-success' : 'btn-warning'}" style="padding:5px 10px;">
                                ${user.bloqueado ? 'Desbloquear' : 'Bloquear'}
                            </button>
                        </td>
                    </tr>
                `;
            });
            
            div.innerHTML += '</table>';

            const selectReset = document.getElementById('usuarioResetPassword');
            const selectAdmin = document.getElementById('usuarioHacerAdmin');
            
            selectReset.innerHTML = '<option value="">Seleccionar usuario...</option>';
            selectAdmin.innerHTML = '<option value="">Seleccionar usuario...</option>';
            
            Object.keys(appData.usuarios).forEach(username => {
                if (username === ADMIN_CONFIG.username) return;
                selectReset.innerHTML += `<option value="${username}">${username}</option>`;
                if (!appData.usuarios[username].esAdmin) {
                    selectAdmin.innerHTML += `<option value="${username}">${username}</option>`;
                }
            });
        }

        function actualizarTabEstadisticas() {
            const usuarios = Object.values(appData.usuarios);
            const totalJugadores = Object.keys(appData.usuarios).length;
            const jugadoresActivos = usuarios.filter(u => !u.bloqueado).length;
            const jugadoresBloqueados = usuarios.filter(u => u.bloqueado).length;
            const totalPredicciones = usuarios.reduce((sum, u) => sum + u.predicciones.length, 0);

            document.getElementById('adminTotalJugadores').textContent = totalJugadores;
            document.getElementById('adminJugadoresActivos').textContent = jugadoresActivos;
            document.getElementById('adminJugadoresBloqueados').textContent = jugadoresBloqueados;
            document.getElementById('adminTotalPredicciones').textContent = totalPredicciones;

            const actividadDiv = document.getElementById('actividadReciente');
            actividadDiv.innerHTML = '<table><tr><th>Usuario</th><th>Último Acceso</th><th>Predicciones</th></tr>';
            
            const usuariosOrdenados = Object.entries(appData.usuarios)
                .sort((a, b) => new Date(b[1].ultimoAcceso) - new Date(a[1].ultimoAcceso));
            
            usuariosOrdenados.forEach(([username, user]) => {
                actividadDiv.innerHTML += `
                    <tr>
                        <td>${username}${user.esAdmin ? ' 👑' : ''}</td>
                        <td>${new Date(user.ultimoAcceso).toLocaleString()}</td>
                        <td>${user.predicciones.length}</td>
                    </tr>
                `;
            });
            
            actividadDiv.innerHTML += '</table>';
        }

        function cambiarTabAdmin(tab) {
            document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
            event.target.classList.add('active');
            
            document.getElementById('tabJugadores').style.display = tab === 'jugadores' ? 'block' : 'none';
            document.getElementById('tabPredicciones').style.display = tab === 'predicciones' ? 'block' : 'none';
            document.getElementById('tabSeguridad').style.display = tab === 'seguridad' ? 'block' : 'none';
            document.getElementById('tabEstadisticas').style.display = tab === 'estadisticas' ? 'block' : 'none';
        }

        function filtrarJugadores() {
            const busqueda = document.getElementById('buscarJugador').value.toLowerCase();
            const filas = document.querySelectorAll('#tablaJugadores tbody tr');
            
            filas.forEach(fila => {
                const username = fila.cells[1].textContent.toLowerCase();
                fila.style.display = username.includes(busqueda) ? '' : 'none';
            });
        }

        function cerrarPanelAdmin() {
            isAdmin = false;
            currentUser = null;
            document.getElementById('adminSection').style.display = 'none';
            document.getElementById('loginSection').style.display = 'block';
        }

        function eliminarPrediccionAdmin(username, index) {
            if (confirm('¿Eliminar esta predicción?')) {
                appData.usuarios[username].predicciones.splice(index, 1);
                appData.usuarios[username].ultimoAcceso = new Date().toISOString();
                guardarDatos();
                actualizarPanelAdmin();
                mostrarAlerta('Predicción eliminada.', 'success');
            }
        }

        function verPrediccionesDe(username) {
            const predicciones = appData.usuarios[username].predicciones;
            if (predicciones.length === 0) {
                alert(`${username} no tiene predicciones.`);
                return;
            }
            
            let mensaje = `Predicciones de ${username}:\n\n`;
            predicciones.forEach(p => {
                mensaje += `${p.partido}: ${p.resultado} (${new Date(p.fecha).toLocaleDateString()})\n`;
            });
            
            alert(mensaje);
        }

        // ============ FUNCIONES DE PREDICCIONES ============
        function guardarPrediccion() {
            if (!currentUser || isAdmin) {
                mostrarAlerta('Debes iniciar sesión como jugador.', 'error');
                return;
            }

            const partido = document.getElementById('partidoParaResultado').value;
            const golesLocal = document.getElementById('golesLocal').value;
            const golesVisitante = document.getElementById('golesVisitante').value;

            if (!partido) {
                mostrarAlerta('Selecciona un partido.', 'error');
                return;
            }

            if (golesLocal < 0 || golesVisitante < 0 || golesLocal > 20 || golesVisitante > 20) {
                mostrarAlerta('Los goles deben estar entre 0 y 20.', 'error');
                return;
            }

            const prediccionExistente = appData.usuarios[currentUser].predicciones.findIndex(
                p => p.partido === partido
            );

            const nuevaPrediccion = {
                partido: partido,
                golesLocal: parseInt(golesLocal),
                golesVisitante: parseInt(golesVisitante),
                resultado: `${golesLocal}-${golesVisitante}`,
                fecha: new Date().toISOString(),
                grupo: obtenerGrupoPartido(partido)
            };

            if (prediccionExistente >= 0) {
                if (confirm('Ya tienes una predicción para este partido. ¿Deseas actualizarla?')) {
                    appData.usuarios[currentUser].predicciones[prediccionExistente] = nuevaPrediccion;
                } else {
                    return;
                }
            } else {
                appData.usuarios[currentUser].predicciones.push(nuevaPrediccion);
            }

            appData.usuarios[currentUser].ultimoAcceso = new Date().toISOString();

            if (guardarDatos()) {
                limpiarFormulario();
                actualizarInterfaz();
                mostrarAlerta('✅ ¡Predicción guardada exitosamente!', 'success');
            }
        }

        function verMisPredicciones() {
            if (!currentUser || isAdmin) return;

            const predicciones = appData.usuarios[currentUser].predicciones;
            const modal = document.getElementById('modalPredicciones');
            const contenido = document.getElementById('contenidoModal');

            if (predicciones.length === 0) {
                contenido.innerHTML = '<p>No tienes predicciones guardadas.</p>';
            } else {
                let html = '<table><tr><th>Partido</th><th>Predicción</th><th>Grupo</th><th>Fecha</th><th>Acción</th></tr>';
                predicciones.forEach((p, index) => {
                    html += `
                        <tr>
                            <td>${p.partido}</td>
                            <td><strong>${p.resultado}</strong></td>
                            <td>${p.grupo}</td>
                            <td>${new Date(p.fecha).toLocaleDateString()}</td>
                            <td><button onclick="eliminarPrediccion(${index})" class="btn-danger" style="padding:5px 10px;">Eliminar</button></td>
                        </tr>
                    `;
                });
                html += '</table>';
                
                html += `
                    <div style="margin-top:15px;">
                        <button onclick="exportarMisPrediccionesCSV()" class="btn-success">📥 CSV</button>
                        <button onclick="exportarMisPrediccionesPDF()" class="btn-info">📄 PDF</button>
                    </div>
                `;
                
                contenido.innerHTML = html;
            }

            modal.style.display = 'flex';
        }

        function eliminarPrediccion(index) {
            if (!currentUser || isAdmin) return;
            
            if (confirm('¿Estás seguro de eliminar esta predicción?')) {
                appData.usuarios[currentUser].predicciones.splice(index, 1);
                appData.usuarios[currentUser].ultimoAcceso = new Date().toISOString();
                guardarDatos();
                verMisPredicciones();
                actualizarInterfaz();
                mostrarAlerta('Predicción eliminada.', 'success');
            }
        }

        function cerrarModal() {
            document.getElementById('modalPredicciones').style.display = 'none';
        }

        function generarAleatorio() {
            document.getElementById('golesLocal').value = Math.floor(Math.random() * 5);
            document.getElementById('golesVisitante').value = Math.floor(Math.random() * 5);
        }

        function limpiarFormulario() {
            document.getElementById('golesLocal').value = 0;
            document.getElementById('golesVisitante').value = 0;
        }

        function limpiarFormularioRegistro() {
            document.getElementById('registroUsuario').value = '';
            document.getElementById('registroEmail').value = '';
            document.getElementById('registroPassword').value = '';
            document.getElementById('registroPasswordConfirm').value = '';
            document.getElementById('passwordStrength').className = 'password-strength';
        }

        // ============ FUNCIONES DE PARTIDOS ============
        function mostrarPartidos() {
            const fechaSeleccionada = document.getElementById('fecha').value;
            const partidosSelect = document.getElementById('partidoParaResultado');
            
            partidosSelect.innerHTML = '';
            partidosFiltrados = cronogramaFifa[fechaSeleccionada] || [];
            
            if (partidosFiltrados.length === 0) {
                document.getElementById('partidos').innerHTML = '<p>No hay partidos para esta fecha.</p>';
                return;
            }
            
            let html = '<table><tr><th>Hora</th><th>Partido</th><th>Grupo</th><th>Estadio</th></tr>';
            partidosFiltrados.forEach(p => {
                html += `<tr>
                    <td>${p.hora}</td>
                    <td><strong>${p.equipos}</strong></td>
                    <td><span class="badge badge-info">${p.grupo}</span></td>
                    <td>${p.estadio}</td>
                </tr>`;
                
                const option = document.createElement('option');
                option.value = p.equipos;
                option.textContent = `${p.equipos} (${p.grupo})`;
                partidosSelect.appendChild(option);
            });
            html += '</table>';
            
            document.getElementById('partidos').innerHTML = html;
        }

        function filtrarPartidos() {
            const busqueda = document.getElementById('buscarPartido').value.toLowerCase();
            if (!partidosFiltrados.length) return;
            
            const filtrados = partidosFiltrados.filter(p => 
                p.equipos.toLowerCase().includes(busqueda)
            );
            
            if (filtrados.length > 0) {
                let html = '<table><tr><th>Hora</th><th>Partido</th><th>Grupo</th><th>Estadio</th></tr>';
                filtrados.forEach(p => {
                    html += `<tr>
                        <td>${p.hora}</td>
                        <td><strong>${p.equipos}</strong></td>
                        <td><span class="badge badge-info">${p.grupo}</span></td>
                        <td>${p.estadio}</td>
                    </tr>`;
                });
                html += '</table>';
                document.getElementById('partidos').innerHTML = html;
            }
        }

        function obtenerGrupoPartido(nombrePartido) {
            for (let fecha in cronogramaFifa) {
                const partido = cronogramaFifa[fecha].find(p => p.equipos === nombrePartido);
                if (partido) return partido.grupo;
            }
            return 'N/A';
        }

        function cargarFechas() {
            const selector = document.getElementById('fecha');
            selector.innerHTML = '';
            
            const fechas = [
                { fecha: '2026-06-11', label: '📅 11 Jun - Inauguración' },
                { fecha: '2026-06-12', label: '📅 12 Jun' },
                { fecha: '2026-06-13', label: '📅 13 Jun' },
                { fecha: '2026-06-14', label: '📅 14 Jun' },
                { fecha: '2026-06-15', label: '📅 15 Jun' },
                { fecha: '2026-06-16', label: '📅 16 Jun' },
                { fecha: '2026-06-17', label: '📅 17 Jun' },
                { fecha: '2026-06-18', label: '📅 18 Jun' },
                { fecha: '2026-06-24', label: '📅 24 Jun' },
                { fecha: '2026-06-25', label: '📅 25 Jun' },
                { fecha: '2026-06-26', label: '📅 26 Jun' },
                { fecha: '2026-06-27', label: '📅 27 Jun - Cierre' }
            ];
            
            fechas.forEach(f => {
                const option = document.createElement('option');
                option.value = f.fecha;
                option.textContent = f.label;
                selector.appendChild(option);
            });
            
            selector.value = fechas[0].fecha;
        }

        // ============ EXPORTACIONES ============
        function exportarMisPrediccionesCSV() {
            if (!currentUser || isAdmin) return;
            
            const predicciones = appData.usuarios[currentUser].predicciones;
            let csv = 'Partido,Predicción,Grupo,Fecha\n';
            predicciones.forEach(p => {
                csv += `"${p.partido}","${p.resultado}","${p.grupo}","${new Date(p.fecha).toLocaleDateString()}"\n`;
            });
            
            descargarArchivo(csv, `predicciones_${currentUser}.csv`, 'text/csv');
            mostrarAlerta('CSV descargado exitosamente.', 'success');
        }

        function exportarMisPrediccionesPDF() {
            if (!currentUser || isAdmin) return;
            
            try {
                const { jsPDF } = window.jspdf;
                const doc = new jsPDF();
                
                doc.setFontSize(18);
                doc.text(`Predicciones de ${currentUser}`, 14, 20);
                doc.setFontSize(12);
                doc.text(`Generado: ${new Date().toLocaleString()}`, 14, 30);
                
                const predicciones = appData.usuarios[currentUser].predicciones;
                const data = predicciones.map(p => [
                    p.partido, p.resultado, p.grupo, new Date(p.fecha).toLocaleDateString()
                ]);
                
                doc.autoTable({
                    head: [['Partido', 'Predicción', 'Grupo', 'Fecha']],
                    body: data,
                    startY: 40,
                    styles: { fontSize: 10 },
                    headStyles: { fillColor: [26, 58, 26] }
                });
                
                window.open(doc.output('bloburl'));
                mostrarAlerta('PDF generado exitosamente.', 'success');
            } catch (error) {
                console.error('Error al generar PDF:', error);
                mostrarAlerta('Error al generar PDF.', 'error');
            }
        }

        function exportarJugadoresCSV() {
            if (!isAdmin) return;
            
            let csv = 'Estado,Usuario,Email,Predicciones,Último Acceso,Bloqueado\n';
            Object.keys(appData.usuarios).forEach(username => {
                const user = appData.usuarios[username];
                const estado = user.bloqueado ? 'Bloqueado' : 'Activo';
                csv += `"${estado}","${username}","${user.email || ''}","${user.predicciones.length}","${new Date(user.ultimoAcceso).toLocaleString()}","${user.bloqueado ? 'Sí' : 'No'}"\n`;
            });
            
            descargarArchivo(csv, 'jugadores_registrados.csv', 'text/csv');
            mostrarAlerta('Lista de jugadores exportada.', 'success');
        }

        function exportarJugadoresPDF() {
            if (!isAdmin) return;
            
            try {
                const { jsPDF } = window.jspdf;
                const doc = new jsPDF('landscape');
                
                doc.setFontSize(18);
                doc.text('Jugadores Registrados', 14, 20);
                
                const data = Object.keys(appData.usuarios).map(username => {
                    const user = appData.usuarios[username];
                    return [
                        user.bloqueado ? 'Bloqueado' : 'Activo',
                        username,
                        user.email || 'N/A',
                        user.predicciones.length.toString(),
                        new Date(user.ultimoAcceso).toLocaleString()
                    ];
                });
                
                doc.autoTable({
                    head: [['Estado', 'Usuario', 'Email', 'Predicciones', 'Último Acceso']],
                    body: data,
                    startY: 30,
                    styles: { fontSize: 8 },
                    headStyles: { fillColor: [26, 58, 26] }
                });
                
                window.open(doc.output('bloburl'));
                mostrarAlerta('PDF de jugadores generado.', 'success');
            } catch (error) {
                console.error('Error al generar PDF:', error);
                mostrarAlerta('Error al generar PDF.', 'error');
            }
        }

        function exportarPrediccionesCSV() {
            if (!isAdmin) return;
            
            let csv = 'Usuario,Partido,Predicción,Grupo,Fecha\n';
            Object.keys(appData.usuarios).forEach(username => {
                appData.usuarios[username].predicciones.forEach(p => {
                    csv += `"${username}","${p.partido}","${p.resultado}","${p.grupo}","${new Date(p.fecha).toLocaleDateString()}"\n`;
                });
            });
            
            descargarArchivo(csv, 'todas_predicciones.csv', 'text/csv');
            mostrarAlerta('Predicciones exportadas.', 'success');
        }

        function exportarPrediccionesPDF() {
            if (!isAdmin) return;
            
            try {
                const { jsPDF } = window.jspdf;
                const doc = new jsPDF('landscape');
                
                doc.setFontSize(18);
                doc.text('Todas las Predicciones', 14, 20);
                
                const data = [];
                Object.keys(appData.usuarios).forEach(username => {
                    appData.usuarios[username].predicciones.forEach(p => {
                        data.push([username, p.partido, p.resultado, p.grupo, new Date(p.fecha).toLocaleDateString()]);
                    });
                });
                
                doc.autoTable({
                    head: [['Usuario', 'Partido', 'Predicción', 'Grupo', 'Fecha']],
                    body: data,
                    startY: 30,
                    styles: { fontSize: 8 },
                    headStyles: { fillColor: [26, 58, 26] }
                });
                
                window.open(doc.output('bloburl'));
                mostrarAlerta('PDF de predicciones generado.', 'success');
            } catch (error) {
                console.error('Error al generar PDF:', error);
                mostrarAlerta('Error al generar PDF.', 'error');
            }
        }

        function descargarArchivo(contenido, nombreArchivo, tipo) {
            const blob = new Blob([contenido], { type: tipo });
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = nombreArchivo;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        }

        // ============ ACTUALIZACIÓN DE INTERFAZ ============
        function actualizarInterfaz() {
            if (!currentUser || isAdmin) return;
            
            const predicciones = appData.usuarios[currentUser].predicciones;
            document.getElementById('misPredicciones').textContent = predicciones.length;
            document.getElementById('totalJugadores').textContent = Object.keys(appData.usuarios).length;
            
            mostrarPartidos();
        }

        function mostrarAlerta(mensaje, tipo) {
            const alertasAnteriores = document.querySelectorAll('.alert-flotante');
            alertasAnteriores.forEach(a => a.remove());
            
            const alerta = document.createElement('div');
            alerta.className = `alert alert-${tipo} alert-flotante`;
            alerta.textContent = mensaje;
            alerta.style.position = 'fixed';
            alerta.style.top = '80px';
            alerta.style.right = '20px';
            alerta.style.zIndex = '10000';
            alerta.style.maxWidth = '400px';
            alerta.style.boxShadow = '0 5px 15px rgba(0,0,0,0.3)';
            
            document.body.appendChild(alerta);
            
            setTimeout(() => {
                alerta.style.opacity = '0';
                alerta.style.transition = 'opacity 0.5s';
                setTimeout(() => alerta.remove(), 500);
            }, 4000);
        }

        // ============ DATOS DE PARTIDOS ============
        const cronogramaFifa = {
            "2026-06-11": [
                { hora: "15:00", equipos: "México vs Sudáfrica", grupo: "A", estadio: "Ciudad de México" },
                { hora: "22:00", equipos: "Corea del Sur vs República Checa", grupo: "A", estadio: "Guadalajara" }
            ],
            "2026-06-12": [
                { hora: "15:00", equipos: "Canadá vs Bosnia y Herzegovina", grupo: "B", estadio: "Toronto" },
                { hora: "21:00", equipos: "Estados Unidos vs Paraguay", grupo: "D", estadio: "Los Ángeles" }
            ],
            "2026-06-13": [
                { hora: "15:00", equipos: "Catar vs Suiza", grupo: "B", estadio: "Bahía de San Francisco" },
                { hora: "18:00", equipos: "Brasil vs Marruecos", grupo: "C", estadio: "Nueva York/Nueva Jersey" },
                { hora: "21:00", equipos: "Haití vs Escocia", grupo: "C", estadio: "Boston" },
                { hora: "00:00", equipos: "Australia vs Turquía", grupo: "D", estadio: "Vancouver" }
            ],
            "2026-06-14": [
                { hora: "13:00", equipos: "Alemania vs Curazao", grupo: "E", estadio: "Houston" },
                { hora: "16:00", equipos: "Países Bajos vs Japón", grupo: "F", estadio: "Dallas" },
                { hora: "19:00", equipos: "Costa de Marfil vs Ecuador", grupo: "E", estadio: "Filadelfia" },
                { hora: "22:00", equipos: "Suecia vs Túnez", grupo: "F", estadio: "Monterrey" }
            ],
            "2026-06-15": [
                { hora: "12:00", equipos: "España vs Cabo Verde", grupo: "H", estadio: "Atlanta" },
                { hora: "15:00", equipos: "Bélgica vs Egipto", grupo: "G", estadio: "Seattle" },
                { hora: "18:00", equipos: "Arabia Saudita vs Uruguay", grupo: "H", estadio: "Miami" },
                { hora: "21:00", equipos: "Irán vs Nueva Zelanda", grupo: "G", estadio: "Los Ángeles" }
            ],
            "2026-06-16": [
                { hora: "15:00", equipos: "Francia vs Senegal", grupo: "I", estadio: "Nueva York/Nueva Jersey" },
                { hora: "18:00", equipos: "Irak vs Noruega", grupo: "I", estadio: "Boston" },
                { hora: "21:00", equipos: "Argentina vs Argelia", grupo: "J", estadio: "Kansas City" },
                { hora: "00:00", equipos: "Austria vs Jordania", grupo: "J", estadio: "Bahía de San Francisco" }
            ],
            "2026-06-17": [
                { hora: "13:00", equipos: "Portugal vs RD Congo", grupo: "K", estadio: "Houston" },
                { hora: "16:00", equipos: "Inglaterra vs Croacia", grupo: "L", estadio: "Dallas" },
                { hora: "19:00", equipos: "Ghana vs Panamá", grupo: "L", estadio: "Toronto" },
                { hora: "22:00", equipos: "Uzbekistán vs Colombia", grupo: "K", estadio: "Ciudad de México" }
            ],
            "2026-06-18": [
                { hora: "12:00", equipos: "República Checa vs Sudáfrica", grupo: "A", estadio: "Atlanta" },
                { hora: "15:00", equipos: "Suiza vs Bosnia y Herzegovina", grupo: "B", estadio: "Los Ángeles" },
                { hora: "18:00", equipos: "Canadá vs Catar", grupo: "B", estadio: "Vancouver" },
                { hora: "21:00", equipos: "México vs Corea del Sur", grupo: "A", estadio: "Guadalajara" }
            ],
            "2026-06-24": [
                { hora: "15:00", equipos: "Suiza vs Canadá", grupo: "B", estadio: "Vancouver" },
                { hora: "15:00", equipos: "Bosnia y Herzegovina vs Catar", grupo: "B", estadio: "Vancouver" },
                { hora: "18:00", equipos: "Escocia vs Brasil", grupo: "C", estadio: "San Francisco" },
                { hora: "18:00", equipos: "Marruecos vs Haití", grupo: "C", estadio: "San Francisco" },
                { hora: "21:00", equipos: "República Checa vs México", grupo: "A", estadio: "Estadio Azteca" },
                { hora: "21:00", equipos: "Sudáfrica vs Corea del Sur", grupo: "A", estadio: "Estadio Azteca" }
            ],
            "2026-06-25": [
                { hora: "16:00", equipos: "Curazao vs Costa de Marfil", grupo: "E", estadio: "Houston" },
                { hora: "16:00", equipos: "Ecuador vs Alemania", grupo: "E", estadio: "Houston" },
                { hora: "19:00", equipos: "Japón vs Suecia", grupo: "F", estadio: "Dallas" },
                { hora: "19:00", equipos: "Túnez vs Países Bajos", grupo: "F", estadio: "Dallas" },
                { hora: "22:00", equipos: "Turquía vs Estados Unidos", grupo: "D", estadio: "Los Angeles" },
                { hora: "22:00", equipos: "Paraguay vs Australia", grupo: "D", estadio: "Los Angeles" }
            ],
            "2026-06-26": [
                { hora: "15:00", equipos: "Noruega vs Francia", grupo: "I", estadio: "Atlanta" },
                { hora: "15:00", equipos: "Senegal vs Irak", grupo: "I", estadio: "Atlanta" },
                { hora: "20:00", equipos: "Cabo Verde vs Arabia Saudita", grupo: "H", estadio: "Madrid" },
                { hora: "20:00", equipos: "Uruguay vs España", grupo: "H", estadio: "Madrid" },
                { hora: "23:00", equipos: "Egipto vs Irán", grupo: "G", estadio: "Barcelona" },
                { hora: "23:00", equipos: "Nueva Zelanda vs Bélgica", grupo: "G", estadio: "Barcelona" }
            ],
            "2026-06-27": [
                { hora: "17:00", equipos: "Panamá vs Inglaterra", grupo: "L", estadio: "Londres" },
                { hora: "17:00", equipos: "Croacia vs Ghana", grupo: "L", estadio: "Londres" },
                { hora: "19:30", equipos: "Colombia vs Portugal", grupo: "K", estadio: "Lisboa" },
                { hora: "19:30", equipos: "RD Congo vs Uzbekistán", grupo: "K", estadio: "Lisboa" },
                { hora: "22:00", equipos: "Argelia vs Austria", grupo: "J", estadio: "Viena" },
                { hora: "22:00", equipos: "Jordania vs Argentina", grupo: "J", estadio: "Buenos Aires" }
            ]
        };

        // ============ INICIAR APLICACIÓN ============
        window.onload = inicializarApp;
    </script>
</body>
</html>
