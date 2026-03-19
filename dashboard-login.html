<!DOCTYPE html>
<html lang="en">
<head>
  <title>CAS & Watcho Dashboard — Login</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Sora:wght@300;400;600;700&family=DM+Sans:wght@400;500&display=swap" rel="stylesheet">
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #080812;
      --card: rgba(255,255,255,0.04);
      --border: rgba(255,255,255,0.08);
      --accent: #7c3aed;
      --accent2: #06b6d4;
      --grad: linear-gradient(135deg, #7c3aed, #06b6d4);
      --text: #f1f5f9;
      --muted: #94a3b8;
      --error: #f87171;
      --success: #34d399;
    }

    body {
      font-family: 'DM Sans', sans-serif;
      min-height: 100vh;
      background: var(--bg);
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
      position: relative;
    }

    /* ── Animated background ── */
    .bg-orb {
      position: fixed;
      border-radius: 50%;
      filter: blur(80px);
      opacity: 0.18;
      animation: drift 12s ease-in-out infinite alternate;
      pointer-events: none;
    }
    .bg-orb-1 { width: 500px; height: 500px; background: #7c3aed; top: -150px; left: -150px; animation-delay: 0s; }
    .bg-orb-2 { width: 400px; height: 400px; background: #06b6d4; bottom: -100px; right: -100px; animation-delay: 3s; }
    .bg-orb-3 { width: 300px; height: 300px; background: #a855f7; top: 50%; left: 50%; transform: translate(-50%, -50%); animation-delay: 6s; }

    @keyframes drift {
      from { transform: translate(0, 0) scale(1); }
      to   { transform: translate(30px, 20px) scale(1.08); }
    }

    /* Grid overlay */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(255,255,255,0.02) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.02) 1px, transparent 1px);
      background-size: 50px 50px;
      pointer-events: none;
      z-index: 0;
    }

    /* ── Card ── */
    .login-card {
      position: relative;
      z-index: 10;
      width: 420px;
      max-width: calc(100vw - 32px);
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 28px;
      padding: 44px 40px 40px;
      backdrop-filter: blur(24px);
      box-shadow:
        0 0 0 1px rgba(124,58,237,0.1),
        0 32px 80px rgba(0,0,0,0.6),
        inset 0 1px 0 rgba(255,255,255,0.06);
      animation: cardIn 0.7s cubic-bezier(0.34,1.56,0.64,1) both;
    }

    @keyframes cardIn {
      from { opacity: 0; transform: translateY(40px) scale(0.95); }
      to   { opacity: 1; transform: translateY(0) scale(1); }
    }

    /* Glowing top border */
    .login-card::before {
      content: '';
      position: absolute;
      top: 0; left: 10%; right: 10%;
      height: 1px;
      background: var(--grad);
      border-radius: 100%;
      opacity: 0.7;
    }

    /* ── Logo area ── */
    .logo-wrap {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-bottom: 36px;
      animation: fadeUp 0.6s 0.2s both;
    }

    .logo-icon {
      width: 72px; height: 72px;
      border-radius: 20px;
      background: var(--grad);
      display: flex; align-items: center; justify-content: center;
      font-size: 34px;
      margin-bottom: 18px;
      box-shadow: 0 8px 32px rgba(124,58,237,0.4);
      position: relative;
    }

    .logo-icon::after {
      content: '';
      position: absolute;
      inset: -3px;
      border-radius: 23px;
      background: var(--grad);
      opacity: 0.2;
      z-index: -1;
      animation: iconPulse 3s ease-in-out infinite;
    }

    @keyframes iconPulse {
      0%, 100% { transform: scale(1); opacity: 0.2; }
      50% { transform: scale(1.1); opacity: 0.35; }
    }

    .logo-wrap h1 {
      font-family: 'Sora', sans-serif;
      font-size: 22px;
      font-weight: 700;
      color: var(--text);
      letter-spacing: -0.3px;
      text-align: center;
    }

    .logo-wrap p {
      font-size: 13px;
      color: var(--muted);
      margin-top: 6px;
      text-align: center;
    }

    /* ── Form ── */
    .form-group {
      margin-bottom: 18px;
      animation: fadeUp 0.6s 0.35s both;
    }

    label {
      display: block;
      font-size: 12px;
      font-weight: 600;
      color: var(--muted);
      letter-spacing: 0.8px;
      text-transform: uppercase;
      margin-bottom: 8px;
    }

    .input-wrap {
      position: relative;
    }

    .input-wrap input {
      width: 100%;
      padding: 14px 46px 14px 16px;
      background: rgba(255,255,255,0.05);
      border: 1.5px solid var(--border);
      border-radius: 14px;
      color: var(--text);
      font-size: 15px;
      font-family: 'DM Sans', sans-serif;
      outline: none;
      transition: border-color 0.25s, background 0.25s, box-shadow 0.25s;
      letter-spacing: 2px;
    }

    .input-wrap input::placeholder { color: rgba(148,163,184,0.5); letter-spacing: 0; }

    .input-wrap input:focus {
      border-color: var(--accent);
      background: rgba(124,58,237,0.06);
      box-shadow: 0 0 0 4px rgba(124,58,237,0.12);
    }

    .input-wrap input.error {
      border-color: var(--error);
      box-shadow: 0 0 0 4px rgba(248,113,113,0.12);
      animation: shake 0.4s ease;
    }

    @keyframes shake {
      0%, 100% { transform: translateX(0); }
      20%, 60% { transform: translateX(-6px); }
      40%, 80% { transform: translateX(6px); }
    }

    /* Eye toggle */
    .eye-btn {
      position: absolute;
      right: 14px; top: 50%;
      transform: translateY(-50%);
      background: none; border: none;
      color: var(--muted); font-size: 18px;
      cursor: pointer; padding: 4px;
      transition: color 0.2s;
      line-height: 1;
    }
    .eye-btn:hover { color: var(--text); }

    /* ── Error message ── */
    .error-msg {
      display: flex;
      align-items: center;
      gap: 6px;
      color: var(--error);
      font-size: 12.5px;
      margin-top: 8px;
      opacity: 0;
      transform: translateY(-4px);
      transition: all 0.25s;
    }
    .error-msg.show { opacity: 1; transform: translateY(0); }

    /* ── Attempts indicator ── */
    .attempts {
      display: flex;
      gap: 5px;
      margin-top: 10px;
      justify-content: center;
    }
    .attempt-dot {
      width: 8px; height: 8px;
      border-radius: 50%;
      background: var(--border);
      transition: background 0.3s;
    }
    .attempt-dot.used { background: var(--error); }

    /* ── Login button ── */
    .login-btn {
      width: 100%;
      padding: 15px;
      background: var(--grad);
      border: none;
      border-radius: 14px;
      color: white;
      font-family: 'Sora', sans-serif;
      font-size: 15px;
      font-weight: 600;
      cursor: pointer;
      margin-top: 8px;
      letter-spacing: 0.3px;
      position: relative;
      overflow: hidden;
      transition: opacity 0.2s, transform 0.15s;
      box-shadow: 0 6px 24px rgba(124,58,237,0.4);
      animation: fadeUp 0.6s 0.5s both;
    }

    .login-btn:hover { opacity: 0.92; transform: translateY(-1px); }
    .login-btn:active { transform: translateY(1px); }
    .login-btn:disabled { opacity: 0.5; cursor: not-allowed; transform: none; }

    .login-btn .btn-text { transition: opacity 0.2s; }
    .login-btn .spinner {
      position: absolute;
      inset: 0;
      display: flex; align-items: center; justify-content: center;
      opacity: 0;
      transition: opacity 0.2s;
    }
    .login-btn.loading .btn-text { opacity: 0; }
    .login-btn.loading .spinner { opacity: 1; }

    .spinner-ring {
      width: 20px; height: 20px;
      border: 2px solid rgba(255,255,255,0.3);
      border-top-color: white;
      border-radius: 50%;
      animation: spin 0.7s linear infinite;
    }
    @keyframes spin { to { transform: rotate(360deg); } }

    /* ── Locked state ── */
    .locked-msg {
      text-align: center;
      color: var(--error);
      font-size: 13px;
      margin-top: 12px;
      display: none;
    }
    .locked-msg.show { display: block; }

    /* ── Footer ── */
    .card-footer {
      margin-top: 28px;
      text-align: center;
      font-size: 11.5px;
      color: var(--muted);
      animation: fadeUp 0.6s 0.6s both;
      border-top: 1px solid var(--border);
      padding-top: 20px;
    }
    .card-footer span { color: var(--accent2); font-weight: 600; }

    /* ── Success overlay ── */
    .success-overlay {
      position: fixed;
      inset: 0;
      background: var(--bg);
      z-index: 100;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 16px;
      opacity: 0;
      pointer-events: none;
      transition: opacity 0.5s;
    }
    .success-overlay.show { opacity: 1; pointer-events: all; }

    .success-icon {
      width: 80px; height: 80px;
      border-radius: 50%;
      background: rgba(52,211,153,0.15);
      border: 2px solid var(--success);
      display: flex; align-items: center; justify-content: center;
      font-size: 38px;
      animation: successPop 0.5s cubic-bezier(0.34,1.56,0.64,1);
    }
    @keyframes successPop {
      from { transform: scale(0); }
      to   { transform: scale(1); }
    }

    .success-overlay h2 {
      font-family: 'Sora', sans-serif;
      color: var(--text);
      font-size: 20px;
    }
    .success-overlay p { color: var(--muted); font-size: 14px; }

    .progress-bar {
      width: 200px; height: 3px;
      background: var(--border);
      border-radius: 10px;
      overflow: hidden;
      margin-top: 8px;
    }
    .progress-fill {
      height: 100%;
      background: var(--grad);
      border-radius: 10px;
      width: 0%;
      transition: width 2s linear;
    }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(16px); }
      to   { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

<!-- Background orbs -->
<div class="bg-orb bg-orb-1"></div>
<div class="bg-orb bg-orb-2"></div>
<div class="bg-orb bg-orb-3"></div>

<!-- Success Overlay -->
<div class="success-overlay" id="successOverlay">
  <div class="success-icon">✅</div>
  <h2>Access Granted!</h2>
  <p>Redirecting to your dashboard...</p>
  <div class="progress-bar">
    <div class="progress-fill" id="progressFill"></div>
  </div>
</div>

<!-- Login Card -->
<div class="login-card">

  <div class="logo-wrap">
    <div class="logo-icon">📊</div>
    <h1>CAS & Watcho Dashboard</h1>
    <p>Enter your password to access the report</p>
  </div>

  <div class="form-group">
    <label>Password</label>
    <div class="input-wrap">
      <input
        type="password"
        id="passwordInput"
        placeholder="Enter password..."
        onkeydown="if(event.key==='Enter') login()"
        autocomplete="current-password"
      >
      <button class="eye-btn" onclick="toggleEye()" id="eyeBtn">👁️</button>
    </div>
    <div class="error-msg" id="errorMsg">⚠️ Incorrect password. Please try again.</div>
  </div>

  <!-- Attempt dots -->
  <div class="attempts" id="attemptDots">
    <div class="attempt-dot" id="dot1"></div>
    <div class="attempt-dot" id="dot2"></div>
    <div class="attempt-dot" id="dot3"></div>
  </div>

  <button class="login-btn" id="loginBtn" onclick="login()">
    <span class="btn-text">🔓 Access Dashboard</span>
    <span class="spinner"><div class="spinner-ring"></div></span>
  </button>

  <div class="locked-msg" id="lockedMsg">
    🔒 Too many failed attempts. Please refresh the page to try again.
  </div>

  <div class="card-footer">
    Secured by <span>CAS</span> · Unauthorised access is prohibited
  </div>

</div>

<script>
  // ════════════════════════════════
  // 🔑 CHANGE YOUR PASSWORD HERE
  // ════════════════════════════════
  const CORRECT_PASSWORD = "CAS@2025";

  // ── Looker Studio URL ──
  const DASHBOARD_URL = "https://lookerstudio.google.com/reporting/9ceaa1d7-9db6-40ed-9988-ef343db9cd4d";

  // ── Settings ──
  const MAX_ATTEMPTS = 3;
  let attempts = 0;
  let isLocked = false;
  let eyeOpen = false;

  function login() {
    if (isLocked) return;

    const input = document.getElementById('passwordInput');
    const btn = document.getElementById('loginBtn');
    const errorMsg = document.getElementById('errorMsg');
    const entered = input.value;

    if (!entered) {
      input.classList.add('error');
      setTimeout(() => input.classList.remove('error'), 600);
      return;
    }

    // Show loading
    btn.classList.add('loading');
    btn.disabled = true;

    setTimeout(() => {
      btn.classList.remove('loading');
      btn.disabled = false;

      if (entered === CORRECT_PASSWORD) {
        // ✅ Correct password
        errorMsg.classList.remove('show');
        showSuccess();
      } else {
        // ❌ Wrong password
        attempts++;
        input.value = '';
        input.classList.add('error');
        errorMsg.classList.add('show');
        setTimeout(() => input.classList.remove('error'), 600);

        // Mark attempt dot
        const dot = document.getElementById('dot' + attempts);
        if (dot) dot.classList.add('used');

        // Lock after max attempts
        if (attempts >= MAX_ATTEMPTS) {
          isLocked = true;
          btn.disabled = true;
          input.disabled = true;
          errorMsg.classList.remove('show');
          document.getElementById('lockedMsg').classList.add('show');
        }
      }
    }, 800);
  }

  function showSuccess() {
    const overlay = document.getElementById('successOverlay');
    overlay.classList.add('show');

    // Start progress bar
    setTimeout(() => {
      document.getElementById('progressFill').style.width = '100%';
    }, 100);

    // Redirect after 2.2 seconds
    setTimeout(() => {
      window.location.href = DASHBOARD_URL;
    }, 2200);
  }

  function toggleEye() {
    eyeOpen = !eyeOpen;
    const input = document.getElementById('passwordInput');
    const btn = document.getElementById('eyeBtn');
    input.type = eyeOpen ? 'text' : 'password';
    btn.textContent = eyeOpen ? '🙈' : '👁️';
  }

  // Auto focus on load
  window.onload = () => document.getElementById('passwordInput').focus();
</script>
</body>
</html>
