<!--
═══════════════════════════════════════════════════════════════
  QUANTUM DEVELOPER PROFILE — v3.0
  A Living, Breathing GitHub Experience
  Built with pure HTML/CSS animations — no video, no SVG
═══════════════════════════════════════════════════════════════
-->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED GATEWAY HEADER
═══════════════════════════════════════════════════════════════ -->
<div style="position: relative; width: 100%; overflow: hidden; border-radius: 24px; background: linear-gradient(135deg, #0a0a1a 0%, #1a0a2e 40%, #0a1a2e 100%); padding: 40px 20px; margin-bottom: 30px; box-shadow: 0 20px 60px rgba(0,0,0,0.5), inset 0 0 80px rgba(100,50,200,0.1);">

  <!-- Animated particle field background -->
  <div style="position: absolute; top: 0; left: 0; right: 0; bottom: 0; overflow: hidden; pointer-events: none;">
    <div style="position: absolute; width: 200%; height: 200%; top: -50%; left: -50%; background: radial-gradient(circle at 30% 40%, rgba(150,50,255,0.15) 0%, transparent 50%), radial-gradient(circle at 70% 60%, rgba(50,150,255,0.15) 0%, transparent 50%), radial-gradient(circle at 50% 50%, rgba(255,50,150,0.1) 0%, transparent 70%); animation: pulseGlow 4s ease-in-out infinite;"></div>
  </div>

  <!-- Glitch/animated name -->
  <div style="position: relative; z-index: 2;">
    <h1 style="font-size: 48px; font-weight: 900; letter-spacing: 4px; margin: 0 0 10px 0; background: linear-gradient(90deg, #ff6b6b, #c850c0, #4158d0, #00d2ff, #ff6b6b); background-size: 300% 100%; -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; animation: gradientShift 6s linear infinite; text-shadow: none; filter: drop-shadow(0 0 20px rgba(200,80,192,0.5));">
      ALEX QUANTUM
    </h1>

    <!-- Animated typing sequence -->
    <div style="display: inline-block; background: rgba(0,0,0,0.6); border-radius: 12px; padding: 12px 20px; margin: 15px 0; border: 1px solid rgba(150,50,255,0.4); box-shadow: 0 0 30px rgba(150,50,255,0.2);">
      <code style="font-family: 'Courier New', monospace; font-size: 16px; color: #00ff88; white-space: nowrap; overflow: hidden; display: inline-block; animation: typing 3.5s steps(40) infinite, blinkCursor 0.75s step-end infinite; border-right: 2px solid #00ff88;">
        $ initializing_developer.exe --mode=futuristic
      </code>
    </div>
  </div>

  <!-- Animated status bar -->
  <div style="position: relative; z-index: 2; display: flex; gap: 15px; justify-content: center; margin-top: 20px; flex-wrap: wrap;">
    <div style="background: rgba(0,255,136,0.1); border: 1px solid rgba(0,255,136,0.3); border-radius: 20px; padding: 8px 16px; backdrop-filter: blur(10px); animation: floatAnimation 3s ease-in-out infinite;">
      <span style="color: #00ff88; font-size: 14px;">● SYSTEM ONLINE</span>
    </div>
    <div style="background: rgba(200,80,192,0.1); border: 1px solid rgba(200,80,192,0.3); border-radius: 20px; padding: 8px 16px; backdrop-filter: blur(10px); animation: floatAnimation 3s ease-in-out infinite 0.5s;">
      <span style="color: #c850c0; font-size: 14px;">⚡ NEURAL LINK ACTIVE</span>
    </div>
    <div style="background: rgba(65,88,208,0.1); border: 1px solid rgba(65,88,208,0.3); border-radius: 20px; padding: 8px 16px; backdrop-filter: blur(10px); animation: floatAnimation 3s ease-in-out infinite 1s;">
      <span style="color: #4158d0; font-size: 14px;">🌐 QUANTUM CONNECTED</span>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED DIVIDER
═══════════════════════════════════════════════════════════════ -->
<div style="width: 100%; height: 2px; margin: 30px 0; background: linear-gradient(90deg, transparent, #c850c0, #4158d0, #00d2ff, #c850c0, transparent); background-size: 200% 100%; animation: shimmerDivider 3s linear infinite; border-radius: 2px;"></div>

<!-- ═══════════════════════════════════════════════════════════
     INTERACTIVE TERMINAL INTERFACE
═══════════════════════════════════════════════════════════════ -->
<div style="background: rgba(10,10,30,0.8); border-radius: 20px; border: 1px solid rgba(100,100,200,0.3); overflow: hidden; margin: 20px 0; box-shadow: 0 15px 40px rgba(0,0,0,0.4), inset 0 0 30px rgba(50,50,150,0.1);">

  <!-- Terminal header -->
  <div style="background: rgba(20,20,40,0.9); padding: 12px 20px; display: flex; align-items: center; gap: 8px; border-bottom: 1px solid rgba(100,100,200,0.2);">
    <div style="width: 12px; height: 12px; border-radius: 50%; background: #ff6b6b; animation: pulse 2s infinite;"></div>
    <div style="width: 12px; height: 12px; border-radius: 50%; background: #ffd93d; animation: pulse 2s infinite 0.3s;"></div>
    <div style="width: 12px; height: 12px; border-radius: 50%; background: #6bcb77; animation: pulse 2s infinite 0.6s;"></div>
    <span style="color: #666; font-size: 12px; margin-left: 10px; font-family: monospace;">root@quantum:~/experience</span>
  </div>

  <!-- Terminal body with scrolling animation -->
  <div style="padding: 25px; font-family: 'Courier New', monospace; font-size: 14px; line-height: 1.8; position: relative; overflow: hidden;">
    <div style="animation: scrollUp 12s linear infinite;">
      <div style="color: #00ff88;">$ <span style="color: #fff;">whoami</span></div>
      <div style="color: #888; margin-left: 20px;">→ Full-Stack Developer & UI/UX Architect</div>
      <div style="color: #888; margin-left: 20px;">→ 7+ years crafting digital experiences</div>
      
      <div style="margin-top: 15px; color: #00ff88;">$ <span style="color: #fff;">ls ./expertise</span></div>
      <div style="color: #888; margin-left: 20px;">▸ React.js / Next.js / Vue.js</div>
      <div style="color: #888; margin-left: 20px;">▸ Node.js / Python / Go</div>
      <div style="color: #888; margin-left: 20px;">▸ AWS / Docker / Kubernetes</div>
      <div style="color: #888; margin-left: 20px;">▸ PostgreSQL / MongoDB / Redis</div>
      
      <div style="margin-top: 15px; color: #00ff88;">$ <span style="color: #fff;">./run_projects.sh</span></div>
      <div style="color: #c850c0; margin-left: 20px;">[████████████████████] 100% Complete</div>
      <div style="color: #888; margin-left: 20px;">✓ 12 major applications deployed</div>
      <div style="color: #888; margin-left: 20px;">✓ 50+ open source contributions</div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED DIVIDER
═══════════════════════════════════════════════════════════════ -->
<div style="width: 80%; height: 1px; margin: 30px auto; background: linear-gradient(90deg, transparent, #ff6b6b, #ffd93d, transparent); animation: shimmerDivider 2.5s linear infinite reverse; border-radius: 2px; opacity: 0.6;"></div>

<!-- ═══════════════════════════════════════════════════════════
     DYNAMIC PROJECT SHOWCASE
═══════════════════════════════════════════════════════════════ -->
<div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center; margin: 30px 0;">

  <!-- Project Card 1 -->
  <div style="flex: 1; min-width: 280px; background: linear-gradient(145deg, rgba(20,20,50,0.9), rgba(30,10,40,0.9)); border-radius: 16px; padding: 25px; border: 1px solid rgba(200,80,192,0.3); transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); animation: cardEntrance 0.8s ease-out; position: relative; overflow: hidden;">
    
    <!-- Animated glow effect -->
    <div style="position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(circle, rgba(200,80,192,0.1) 0%, transparent 70%); animation: rotateGlow 8s linear infinite; pointer-events: none;"></div>
    
    <div style="position: relative; z-index: 1;">
      <h3 style="color: #c850c0; font-size: 20px; margin: 0 0 15px 0; font-family: 'Segoe UI', sans-serif;">NEURAL NOTES</h3>
      <p style="color: #aaa; font-size: 14px; line-height: 1.6; margin: 0;">AI-powered note-taking with real-time collaboration. Built with React, WebSocket, and TensorFlow.js.</p>
      
      <!-- Animated progress bar -->
      <div style="margin-top: 20px;">
        <div style="display: flex; justify-content: space-between; color: #666; font-size: 12px; margin-bottom: 5px;">
          <span>DEPLOYMENT</span>
          <span style="color: #00ff88;">LIVE</span>
        </div>
        <div style="background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px; overflow: hidden;">
          <div style="background: linear-gradient(90deg, #c850c0, #4158d0); width: 85%; height: 100%; border-radius: 10px; animation: progressFill 2s ease-out;"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 2 -->
  <div style="flex: 1; min-width: 280px; background: linear-gradient(145deg, rgba(20,20,50,0.9), rgba(10,30,50,0.9)); border-radius: 16px; padding: 25px; border: 1px solid rgba(0,210,255,0.3); transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); animation: cardEntrance 0.8s ease-out 0.2s; position: relative; overflow: hidden;">
    
    <div style="position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(circle, rgba(0,210,255,0.1) 0%, transparent 70%); animation: rotateGlow 8s linear infinite reverse; pointer-events: none;"></div>
    
    <div style="position: relative; z-index: 1;">
      <h3 style="color: #00d2ff; font-size: 20px; margin: 0 0 15px 0; font-family: 'Segoe UI', sans-serif;">QUANTUM SHOP</h3>
      <p style="color: #aaa; font-size: 14px; line-height: 1.6; margin: 0;">Headless e-commerce platform with GraphQL, Stripe, and serverless architecture on AWS Lambda.</p>
      
      <div style="margin-top: 20px;">
        <div style="display: flex; justify-content: space-between; color: #666; font-size: 12px; margin-bottom: 5px;">
          <span>PERFORMANCE</span>
          <span style="color: #ffd93d;">OPTIMAL</span>
        </div>
        <div style="background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px; overflow: hidden;">
          <div style="background: linear-gradient(90deg, #00d2ff, #4158d0); width: 95%; height: 100%; border-radius: 10px; animation: progressFill 2s ease-out 0.3s;"></div>
        </div>
      </div>
    </div>
  </div>

  <!-- Project Card 3 -->
  <div style="flex: 1; min-width: 280px; background: linear-gradient(145deg, rgba(20,20,50,0.9), rgba(40,20,30,0.9)); border-radius: 16px; padding: 25px; border: 1px solid rgba(255,107,107,0.3); transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); animation: cardEntrance 0.8s ease-out 0.4s; position: relative; overflow: hidden;">
    
    <div style="position: absolute; top: -50%; left: -50%; width: 200%; height: 200%; background: radial-gradient(circle, rgba(255,107,107,0.1) 0%, transparent 70%); animation: rotateGlow 8s linear infinite 2s; pointer-events: none;"></div>
    
    <div style="position: relative; z-index: 1;">
      <h3 style="color: #ff6b6b; font-size: 20px; margin: 0 0 15px 0; font-family: 'Segoe UI', sans-serif;">DEVORBIT</h3>
      <p style="color: #aaa; font-size: 14px; line-height: 1.6; margin: 0;">Developer collaboration platform with real-time code sharing, voice chat, and CI/CD integration.</p>
      
      <div style="margin-top: 20px;">
        <div style="display: flex; justify-content: space-between; color: #666; font-size: 12px; margin-bottom: 5px;">
          <span>USERS</span>
          <span style="color: #00ff88;">10K+</span>
        </div>
        <div style="background: rgba(255,255,255,0.1); border-radius: 10px; height: 6px; overflow: hidden;">
          <div style="background: linear-gradient(90deg, #ff6b6b, #ffd93d); width: 75%; height: 100%; border-radius: 10px; animation: progressFill 2s ease-out 0.6s;"></div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED DIVIDER
═══════════════════════════════════════════════════════════════ -->
<div style="width: 60%; height: 2px; margin: 30px auto; background: linear-gradient(90deg, transparent, #00ff88, #00d2ff, transparent); animation: shimmerDivider 2s linear infinite; border-radius: 2px; opacity: 0.8;"></div>

<!-- ═══════════════════════════════════════════════════════════
     SKILLS ORBITAL SYSTEM
═══════════════════════════════════════════════════════════════ -->
<div style="background: rgba(10,10,30,0.6); border-radius: 20px; padding: 40px 20px; margin: 30px 0; position: relative; overflow: hidden;">
  
  <h3 style="text-align: center; color: #fff; font-size: 24px; margin-bottom: 30px; background: linear-gradient(90deg, #00ff88, #00d2ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">
    ⚡ TECH STACK MATRIX
  </h3>

  <div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">
    
    <!-- Skill chips with hover animation -->
    <div style="background: rgba(65,88,208,0.2); border: 1px solid rgba(65,88,208,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite;">
      <span style="color: #4158d0; font-weight: bold;">React</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Advanced</span>
    </div>

    <div style="background: rgba(0,210,255,0.2); border: 1px solid rgba(0,210,255,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite 0.2s;">
      <span style="color: #00d2ff; font-weight: bold;">Node.js</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Expert</span>
    </div>

    <div style="background: rgba(200,80,192,0.2); border: 1px solid rgba(200,80,192,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite 0.4s;">
      <span style="color: #c850c0; font-weight: bold;">Python</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Advanced</span>
    </div>

    <div style="background: rgba(255,107,107,0.2); border: 1px solid rgba(255,107,107,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite 0.6s;">
      <span style="color: #ff6b6b; font-weight: bold;">AWS</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Professional</span>
    </div>

    <div style="background: rgba(255,217,61,0.2); border: 1px solid rgba(255,217,61,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite 0.8s;">
      <span style="color: #ffd93d; font-weight: bold;">Docker</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Expert</span>
    </div>

    <div style="background: rgba(107,203,119,0.2); border: 1px solid rgba(107,203,119,0.5); border-radius: 25px; padding: 12px 20px; transition: all 0.3s ease; animation: skillPulse 3s infinite 1s;">
      <span style="color: #6bcb77; font-weight: bold;">GraphQL</span>
      <span style="color: #666; font-size: 12px; margin-left: 8px;">Advanced</span>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED CONTRIBUTION GRAPH
═══════════════════════════════════════════════════════════════ -->
<div align="center" style="margin: 40px 0;">
  <h3 style="color: #fff; font-size: 22px; margin-bottom: 20px; background: linear-gradient(90deg, #ff6b6b, #c850c0, #4158d0); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text;">
    📊 ACTIVITY MATRIX
  </h3>
  
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical&hide_border=true&bg_color=0a0a1a&title_color=c850c0&icon_color=00d2ff&text_color=ffffff" alt="GitHub Stats" style="border-radius: 15px; margin: 10px; animation: floatAnimation 4s ease-in-out infinite;" />
  
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=radical&hide_border=true&background=0a0a1a&stroke=c850c0&ring=4158d0&fire=ff6b6b" alt="GitHub Streak" style="border-radius: 15px; margin: 10px; animation: floatAnimation 4s ease-in-out infinite 0.5s;" />
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATED CONNECT SECTION
═══════════════════════════════════════════════════════════════ -->
<div style="text-align: center; margin: 40px 0 20px 0; position: relative;">
  
  <!-- Animated orbit rings -->
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 300px; height: 300px; border: 1px solid rgba(200,80,192,0.2); border-radius: 50%; animation: orbitRotate 10s linear infinite; pointer-events: none;"></div>
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 250px; height: 250px; border: 1px solid rgba(65,88,208,0.2); border-radius: 50%; animation: orbitRotate 8s linear infinite reverse; pointer-events: none;"></div>
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 200px; height: 200px; border: 1px solid rgba(0,210,255,0.2); border-radius: 50%; animation: orbitRotate 6s linear infinite; pointer-events: none;"></div>
  
  <div style="position: relative; z-index: 1;">
    <h3 style="color: #00ff88; font-size: 20px; margin-bottom: 20px; font-family: monospace;">$ establish_connection --secure</h3>
    
    <div style="display: flex; gap: 15px; justify-content: center; flex-wrap: wrap;">
      <a href="https://github.com/YOUR_USERNAME" style="text-decoration: none; background: linear-gradient(135deg, #4158d0, #c850c0); padding: 12px 24px; border-radius: 25px; color: white; font-weight: bold; transition: all 0.3s ease; animation: buttonGlow 2s infinite;">
        GITHUB
      </a>
      <a href="https://linkedin.com/in/YOUR_USERNAME" style="text-decoration: none; background: linear-gradient(135deg, #0077b5, #00a0dc); padding: 12px 24px; border-radius: 25px; color: white; font-weight: bold; transition: all 0.3s ease; animation: buttonGlow 2s infinite 0.5s;">
        LINKEDIN
      </a>
      <a href="mailto:YOUR_EMAIL" style="text-decoration: none; background: linear-gradient(135deg, #ff6b6b, #ffd93d); padding: 12px 24px; border-radius: 25px; color: white; font-weight: bold; transition: all 0.3s ease; animation: buttonGlow 2s infinite 1s;">
        EMAIL
      </a>
    </div>
  </div>
</div>

<!-- ═══════════════════════════════════════════════════════════
     ANIMATION KEYFRAMES
═══════════════════════════════════════════════════════════════ -->
<style>
  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  
  @keyframes typing {
    0%, 20% { width: 0; }
    70%, 90% { width: 100%; }
    100% { width: 0; }
  }
  
  @keyframes blinkCursor {
    0%, 50% { border-color: #00ff88; }
    50.01%, 100% { border-color: transparent; }
  }
  
  @keyframes pulseGlow {
    0%, 100% { opacity: 0.5; }
    50% { opacity: 1; }
  }
  
  @keyframes floatAnimation {
    0%, 100% { transform: translateY(0px); }
    50% { transform: translateY(-10px); }
  }
  
  @keyframes shimmerDivider {
    0% { background-position: 200% 0; }
    100% { background-position: -200% 0; }
  }
  
  @keyframes scrollUp {
    0% { transform: translateY(0); }
    100% { transform: translateY(-50%); }
  }
  
  @keyframes progressFill {
    from { width: 0; }
    to { width: 100%; }
  }
  
  @keyframes cardEntrance {
    from { opacity: 0; transform: translateY(30px) scale(0.9); }
    to { opacity: 1; transform: translateY(0) scale(1); }
  }
  
  @keyframes rotateGlow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  
  @keyframes skillPulse {
    0%, 100% { box-shadow: 0 0 10px rgba(200,80,192,0.3); }
    50% { box-shadow: 0 0 20px rgba(200,80,192,0.6); }
  }
  
  @keyframes orbitRotate {
    from { transform: translate(-50%, -50%) rotate(0deg); }
    to { transform: translate(-50%, -50%) rotate(360deg); }
  }
  
  @keyframes buttonGlow {
    0%, 100% { box-shadow: 0 0 10px rgba(200,80,192,0.5); }
    50% { box-shadow: 0 0 25px rgba(200,80,192,0.8); }
  }
  
  @keyframes pulse {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.3; }
  }
</style>

<!-- ═══════════════════════════════════════════════════════════
     MOBILE RESPONSIVE OVERRIDES
═══════════════════════════════════════════════════════════════ -->
<style>
  @media (max-width: 768px) {
    h1 { font-size: 32px !important; letter-spacing: 2px !important; }
    div[style*="min-width: 280px"] { min-width: 100% !important; }
    div[style*="width: 300px"], div[style*="width: 250px"], div[style*="width: 200px"] { display: none; }
    code { font-size: 12px !important; }
  }
</style>

<!-- ═══════════════════════════════════════════════════════════
     FOOTER SIGNATURE
═══════════════════════════════════════════════════════════════ -->
<div style="text-align: center; margin-top: 50px; padding: 20px; position: relative;">
  <div style="width: 100%; height: 1px; background: linear-gradient(90deg, transparent, rgba(200,80,192,0.5), transparent); margin-bottom: 20px;"></div>
  <p style="color: #666; font-size: 12px; margin: 0; font-family: monospace; animation: pulseGlow 3s infinite;">
    <span style="color: #c850c0;">$</span> system_ready <span style="color: #00ff88;">●</span> connection_active <span style="color: #00d2ff;">●</span> creativity_flowing
  </p>
  <p style="color: #444; font-size: 10px; margin-top: 10px; font-family: monospace;">
    © 2024 • Crafted with ⚡ in the quantum realm
  </p>
</div>

</div>
