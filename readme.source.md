[readme.source (1).md](https://github.com/user-attachments/files/35108536/readme.source.1.md)
```aura width=830 height=280
<div style={{ display: 'flex', position: 'relative', width: '100%', height: '100%', background: '#0a0d0c', borderRadius: 24, overflow: 'hidden', border: '1px solid rgba(14,177,142,0.45)' }}>
  <svg width="830" height="280" viewBox="0 0 830 280" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="gPurple" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#0eb18e" stopOpacity="0.85" />
        <stop offset="100%" stopColor="#0eb18e" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="gMagenta" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#0a8a70" stopOpacity="0.55" />
        <stop offset="100%" stopColor="#0a8a70" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="gCyan" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#6ee7c8" stopOpacity="0.45" />
        <stop offset="100%" stopColor="#6ee7c8" stopOpacity="0" />
      </radialGradient>
    </defs>
    <ellipse cx="120" cy="60" rx="260" ry="160" fill="url(#gPurple)">
      <animate attributeName="cx" values="120;260;120" dur="9s" repeatCount="indefinite" />
      <animate attributeName="cy" values="60;110;60" dur="9s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="640" cy="230" rx="240" ry="140" fill="url(#gMagenta)">
      <animate attributeName="cx" values="640;540;640" dur="11s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="760" cy="40" rx="200" ry="120" fill="url(#gCyan)">
      <animate attributeName="cy" values="40;100;40" dur="7s" repeatCount="indefinite" />
    </ellipse>
    <circle cx="690" cy="140" r="96" fill="none" stroke="#0eb18e" strokeOpacity="0.55" strokeWidth="1.5" strokeDasharray="4 10">
      <animateTransform attributeName="transform" type="rotate" from="0 690 140" to="360 690 140" dur="30s" repeatCount="indefinite" />
    </circle>
    <circle cx="690" cy="140" r="64" fill="none" stroke="#6ee7c8" strokeOpacity="0.55" strokeWidth="1.5" strokeDasharray="2 8">
      <animateTransform attributeName="transform" type="rotate" from="360 690 140" to="0 690 140" dur="22s" repeatCount="indefinite" />
    </circle>
    <circle cx="560" cy="60" r="3" fill="#ffffff">
      <animate attributeName="opacity" values="0.1;1;0.1" dur="3s" repeatCount="indefinite" />
    </circle>
    <circle cx="470" cy="220" r="2" fill="#ffffff">
      <animate attributeName="opacity" values="1;0.1;1" dur="4s" repeatCount="indefinite" />
    </circle>
    <circle cx="790" cy="230" r="2.5" fill="#ffffff">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="5s" repeatCount="indefinite" />
    </circle>
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', justifyContent: 'center', alignItems: 'flex-start', width: '100%', height: '100%', padding: '0 56px' }}>
    <div style={{ display: 'flex', alignItems: 'center', padding: '6px 16px', borderRadius: 999, border: '1px solid rgba(14,177,142,0.6)', background: 'rgba(14,177,142,0.12)', color: '#bff3e4', fontSize: 14, letterSpacing: 3 }}>
      <div style={{ display: 'flex', width: 8, height: 8, borderRadius: 999, background: '#6ee7c8', marginRight: 10 }} />
      <div style={{ display: 'flex' }}>PORTO DIGITAL  ·  RECIFE, PE</div>
    </div>
    <div style={{ display: 'flex', marginTop: 20, color: '#ffffff', fontSize: 68, fontWeight: 700, letterSpacing: -2 }}>Sammuel Victor</div>
    <div style={{ display: 'flex', marginTop: 4, color: '#9fb5af', fontSize: 24 }}>Front-end Developer  ·  UX/UI  ·  Estudante de Sistemas para Internet</div>
    <div style={{ display: 'flex', marginTop: 24 }}>
      <div style={{ display: 'flex', padding: '7px 16px', marginRight: 10, borderRadius: 10, background: 'rgba(255,255,255,0.06)', border: '1px solid rgba(255,255,255,0.14)', color: '#f1f5f4', fontSize: 15 }}>React</div>
      <div style={{ display: 'flex', padding: '7px 16px', marginRight: 10, borderRadius: 10, background: 'rgba(255,255,255,0.06)', border: '1px solid rgba(255,255,255,0.14)', color: '#f1f5f4', fontSize: 15 }}>Spring Boot</div>
      <div style={{ display: 'flex', padding: '7px 16px', marginRight: 10, borderRadius: 10, background: 'rgba(255,255,255,0.06)', border: '1px solid rgba(255,255,255,0.14)', color: '#f1f5f4', fontSize: 15 }}>Tailwind</div>
    </div>
  </div>

  <div style={{ display: 'flex', position: 'absolute', top: 0, left: 560, width: 260, height: 280, alignItems: 'center', justifyContent: 'center', color: '#ffffff', fontSize: 52, fontWeight: 700 }}>{'</>'}</div>
</div>
```

```aura width=150 height=44 link="https://www.linkedin.com/in/sammuel-victor/" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/linkedin/ffffff"
  text="LinkedIn"
  backgroundColor="#0a0d0c"
  width={150}
  height={44}
  iconSize={20}
  gradientStops={[
    { offset: '0%', color: '#0eb18e' },
    { offset: '50%', color: '#6ee7c8' },
    { offset: '100%', color: '#0a8a70' },
  ]}
/>
```

```aura width=150 height=44 link="https://www.instagram.com/samv1ctor" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/instagram/ffffff"
  text="Instagram"
  backgroundColor="#0a0d0c"
  width={150}
  height={44}
  iconSize={20}
  gradientStops={[
    { offset: '0%', color: '#0a8a70' },
    { offset: '50%', color: '#0eb18e' },
    { offset: '100%', color: '#6ee7c8' },
  ]}
/>
```

```aura width=150 height=44 link="https://sammuelvictor.vercel.app/" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/vercel/ffffff"
  text="Portfólio"
  backgroundColor="#0a0d0c"
  width={150}
  height={44}
  iconSize={20}
  gradientStops={[
    { offset: '0%', color: '#6ee7c8' },
    { offset: '50%', color: '#0a8a70' },
    { offset: '100%', color: '#0eb18e' },
  ]}
/>
```

```aura width=150 height=44 link="mailto:samvss13@gmail.com" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/gmail/ffffff"
  text="E-mail"
  backgroundColor="#0a0d0c"
  width={150}
  height={44}
  iconSize={20}
  gradientStops={[
    { offset: '0%', color: '#0eb18e' },
    { offset: '50%', color: '#0a8a70' },
    { offset: '100%', color: '#6ee7c8' },
  ]}
/>
```

```aura width=830 height=64
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%' }}>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(14,177,142,0), rgba(14,177,142,0.9))' }} />
  <div style={{ display: 'flex', padding: '9px 26px', margin: '0 18px', borderRadius: 999, border: '1px solid rgba(14,177,142,0.6)', background: '#111716', color: '#f1f5f4', fontSize: 18, fontWeight: 700, letterSpacing: 4 }}>SOBRE MIM</div>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(14,177,142,0.9), rgba(14,177,142,0))' }} />
</div>
```

```aura width=830 height=320
<div style={{ display: 'flex', width: '100%', height: '100%', padding: 34, borderRadius: 24, border: '1px solid rgba(14,177,142,0.35)', background: 'linear-gradient(135deg, #101a17 0%, #0a0d0c 100%)' }}>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, justifyContent: 'center', paddingRight: 34 }}>
    <div style={{ display: 'flex', color: '#ffffff', fontSize: 30, fontWeight: 700 }}>Olá, eu sou o Sammuel</div>
    <div style={{ display: 'flex', marginTop: 12, color: '#9fb5af', fontSize: 17, lineHeight: 1.5 }}>Estudante de Sistemas para Internet na UNICAP e residente em tecnologia no Porto Digital. Gosto de transformar ideias em interfaces bonitas e funcionais, e de aprender algo novo a cada projeto.</div>
    <div style={{ display: 'flex', alignItems: 'center', marginTop: 20 }}>
      <div style={{ display: 'flex', width: 8, height: 8, borderRadius: 999, background: '#0eb18e', marginRight: 12 }} />
      <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Projetos em equipe: Spring Boot no back + React no front</div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', marginTop: 10 }}>
      <div style={{ display: 'flex', width: 8, height: 8, borderRadius: 999, background: '#0a8a70', marginRight: 12 }} />
      <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Robótica e eletrônica com Arduino e C++</div>
    </div>
    <div style={{ display: 'flex', alignItems: 'center', marginTop: 10 }}>
      <div style={{ display: 'flex', width: 8, height: 8, borderRadius: 999, background: '#6ee7c8', marginRight: 12 }} />
      <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Aprofundando em React, Spring Boot e Python</div>
    </div>
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', width: 320, padding: 20, borderRadius: 16, background: '#0a0d0c', border: '1px solid rgba(255,255,255,0.12)' }}>
    <div style={{ display: 'flex', marginBottom: 16 }}>
      <div style={{ display: 'flex', width: 11, height: 11, borderRadius: 999, background: '#ff5f57', marginRight: 7 }} />
      <div style={{ display: 'flex', width: 11, height: 11, borderRadius: 999, background: '#febc2e', marginRight: 7 }} />
      <div style={{ display: 'flex', width: 11, height: 11, borderRadius: 999, background: '#28c840' }} />
    </div>
    <div style={{ display: 'flex', fontSize: 16, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#0a8a70', marginRight: 8 }}>const</div>
      <div style={{ display: 'flex', color: '#6ee7c8', marginRight: 8 }}>sammuel</div>
      <div style={{ display: 'flex', color: '#f1f5f4' }}>= {'{'}</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, paddingLeft: 20, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#9fb5af', marginRight: 8 }}>local:</div>
      <div style={{ display: 'flex', color: '#a6e22e' }}>"Recife, PE",</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, paddingLeft: 20, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#9fb5af', marginRight: 8 }}>curso:</div>
      <div style={{ display: 'flex', color: '#a6e22e' }}>"Sistemas p/ Internet",</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, paddingLeft: 20, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#9fb5af', marginRight: 8 }}>foco:</div>
      <div style={{ display: 'flex', color: '#a6e22e' }}>"Front-end + UX/UI",</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, paddingLeft: 20, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#9fb5af', marginRight: 8 }}>hobby:</div>
      <div style={{ display: 'flex', color: '#a6e22e' }}>"Arduino + C++",</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, paddingLeft: 20, marginBottom: 6 }}>
      <div style={{ display: 'flex', color: '#9fb5af', marginRight: 8 }}>aprendendo:</div>
      <div style={{ display: 'flex', color: '#febc2e' }}>true,</div>
    </div>
    <div style={{ display: 'flex', fontSize: 16, color: '#f1f5f4' }}>{'};'}</div>
  </div>
</div>
```

```aura width=830 height=64
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%' }}>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(110,231,200,0), rgba(110,231,200,0.9))' }} />
  <div style={{ display: 'flex', padding: '9px 26px', margin: '0 18px', borderRadius: 999, border: '1px solid rgba(110,231,200,0.6)', background: '#111716', color: '#f1f5f4', fontSize: 18, fontWeight: 700, letterSpacing: 4 }}>STACK</div>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(110,231,200,0.9), rgba(110,231,200,0))' }} />
</div>
```

```aura width=830 height=250
<div style={{ display: 'flex', width: '100%', height: '100%' }}>
  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, marginRight: 16, padding: 26, borderRadius: 24, border: '1px solid rgba(14,177,142,0.35)', background: 'linear-gradient(135deg, #101a17 0%, #0a0d0c 100%)' }}>
    <div style={{ display: 'flex', color: '#0eb18e', fontSize: 14, letterSpacing: 3, marginBottom: 6 }}>FERRAMENTAS</div>
    <div style={{ display: 'flex', color: '#ffffff', fontSize: 24, fontWeight: 700, marginBottom: 18 }}>Tecnologias</div>
    <div style={{ display: 'flex', flexWrap: 'wrap' }}>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#ED8B00', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Java</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#E34F26', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>HTML5</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#1572B6', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>CSS3</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#F7DF1E', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>JavaScript</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#06B6D4', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Tailwind CSS</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#4479A1', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>MySQL</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#17201d', border: '1px solid rgba(255,255,255,0.12)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#F05032', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Git</div>
      </div>
    </div>
  </div>

  <div style={{ display: 'flex', flexDirection: 'column', flex: 1, padding: 26, borderRadius: 24, border: '1px solid rgba(110,231,200,0.35)', background: 'linear-gradient(135deg, #0e1c19 0%, #0a0d0c 100%)' }}>
    <div style={{ display: 'flex', color: '#6ee7c8', fontSize: 14, letterSpacing: 3, marginBottom: 6 }}>EVOLUINDO</div>
    <div style={{ display: 'flex', color: '#ffffff', fontSize: 24, fontWeight: 700, marginBottom: 18 }}>Estudando agora</div>
    <div style={{ display: 'flex', flexWrap: 'wrap' }}>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#14211e', border: '1px solid rgba(110,231,200,0.3)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#61DAFB', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>React</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#14211e', border: '1px solid rgba(110,231,200,0.3)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#6DB33F', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Spring Boot</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#14211e', border: '1px solid rgba(110,231,200,0.3)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#FFD43B', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Python</div>
      </div>
      <div style={{ display: 'flex', alignItems: 'center', padding: '8px 14px', marginRight: 10, marginBottom: 10, borderRadius: 12, background: '#14211e', border: '1px solid rgba(110,231,200,0.3)' }}>
        <div style={{ display: 'flex', width: 9, height: 9, borderRadius: 999, background: '#339933', marginRight: 10 }} />
        <div style={{ display: 'flex', color: '#f1f5f4', fontSize: 16 }}>Node.js</div>
      </div>
    </div>
  </div>
</div>
```

```aura width=830 height=64
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%' }}>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(10,138,112,0), rgba(10,138,112,0.9))' }} />
  <div style={{ display: 'flex', padding: '9px 26px', margin: '0 18px', borderRadius: 999, border: '1px solid rgba(10,138,112,0.6)', background: '#111716', color: '#f1f5f4', fontSize: 18, fontWeight: 700, letterSpacing: 4 }}>ESTATÍSTICAS</div>
  <div style={{ display: 'flex', flex: 1, height: 1, background: 'linear-gradient(90deg, rgba(10,138,112,0.9), rgba(10,138,112,0))' }} />
</div>
```

<div align="center">
  <a href="https://github.com/Sammuelvss">
    <img height="170" alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=Sammuelvss&show_icons=true&hide_border=true&bg_color=111716&title_color=0eb18e&text_color=f1f5f4&icon_color=6ee7c8&ring_color=0eb18e" />
  </a>
  <a href="https://github.com/Sammuelvss">
    <img height="170" alt="GitHub Streak" src="https://streak-stats.demolab.com/?user=Sammuelvss&background=111716&border=1f2b28&stroke=1f2b28&ring=0eb18e&fire=6ee7c8&currStreakNum=f1f5f4&sideNums=f1f5f4&currStreakLabel=0eb18e&sideLabels=9fb5af&dates=9fb5af" />
  </a>
</div>

```aura width=830 height=150
<div style={{ display: 'flex', position: 'relative', width: '100%', height: '100%', background: '#0a0d0c', borderRadius: 24, overflow: 'hidden', border: '1px solid rgba(14,177,142,0.45)' }}>
  <svg width="830" height="150" viewBox="0 0 830 150" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="fPurple" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#0eb18e" stopOpacity="0.8" />
        <stop offset="100%" stopColor="#0eb18e" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="fCyan" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="#6ee7c8" stopOpacity="0.45" />
        <stop offset="100%" stopColor="#6ee7c8" stopOpacity="0" />
      </radialGradient>
    </defs>
    <ellipse cx="200" cy="140" rx="280" ry="110" fill="url(#fPurple)">
      <animate attributeName="cx" values="200;420;200" dur="10s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="650" cy="10" rx="240" ry="100" fill="url(#fCyan)">
      <animate attributeName="cx" values="650;450;650" dur="12s" repeatCount="indefinite" />
    </ellipse>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center', width: '100%', height: '100%' }}>
    <div style={{ display: 'flex', color: '#ffffff', fontSize: 28, fontWeight: 700 }}>Sempre estudando algo novo.</div>
    <div style={{ display: 'flex', marginTop: 8, color: '#9fb5af', fontSize: 16 }}>Obrigado por passar por aqui  ·  fique à vontade para chamar</div>
  </div>
</div>
```
