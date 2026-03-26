

<!DOCTYPE html>
<html lang="az">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1"/>
<title>MathClass</title>
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Syne:wght@700;800&display=swap" rel="stylesheet"/>
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --bg:#0d1117; --bg2:#161b22; --bg3:#1c2333; --border:#30363d; --border2:#21262d;
  --text:#e6edf3; --text2:#8b949e; --text3:#484f58;
  --green:#22c55e; --green-s:rgba(34,197,94,.13);
  --orange:#f59e0b; --orange-s:rgba(245,158,11,.13);
  --red:#ef4444; --red-s:rgba(239,68,68,.13);
  --purple:#a855f7; --purple-s:rgba(168,85,247,.13);
  --radius:14px; --radius-s:8px;
  /* role colors injected by JS */
  --acc:#3b82f6; --acc2:#60a5fa; --acc-s:rgba(59,130,246,.13);
}
html{scroll-behavior:smooth}
body{font-family:'Plus Jakarta Sans',sans-serif;background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden}

/* ── UTILITIES ── */
.hide{display:none!important}
.badge{display:inline-flex;align-items:center;font-size:11px;font-weight:600;padding:3px 9px;border-radius:20px}
.badge.g{background:var(--green-s);color:var(--green)}
.badge.o{background:var(--orange-s);color:var(--orange)}
.badge.r{background:var(--red-s);color:var(--red)}
.badge.b{background:var(--acc-s);color:var(--acc2)}
.badge.p{background:var(--purple-s);color:var(--purple)}

/* ── LOGIN ── */
#loginScreen{
  min-height:100vh;display:flex;flex-direction:column;
  align-items:center;justify-content:center;padding:24px 16px;
  background:radial-gradient(ellipse 70% 50% at 20% 10%,rgba(59,130,246,.14) 0%,transparent 60%),
             radial-gradient(ellipse 50% 60% at 80% 90%,rgba(168,85,247,.10) 0%,transparent 55%),var(--bg);
}
.l-logo{display:flex;align-items:center;gap:12px;margin-bottom:36px;animation:fadeUp .6s ease both}
.l-logo-icon{width:50px;height:50px;border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:26px;box-shadow:0 0 32px rgba(59,130,246,.35);background:linear-gradient(135deg,#3b82f6,#1d4ed8)}
.l-logo-text{font-family:'Syne',sans-serif;font-size:26px;font-weight:800;letter-spacing:-.02em}
.l-logo-text span{color:var(--acc2)}
.l-card{background:var(--bg2);border:1px solid var(--border);border-radius:20px;padding:36px 28px;width:100%;max-width:400px;box-shadow:0 4px 32px rgba(0,0,0,.5);animation:fadeUp .7s .1s ease both}
.l-title{font-family:'Syne',sans-serif;font-size:22px;font-weight:800;margin-bottom:4px}
.l-sub{font-size:13px;color:var(--text2);margin-bottom:28px}
.role-sw{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-bottom:24px}
.role-btn{padding:12px 8px;border-radius:10px;border:1.5px solid var(--border);background:transparent;color:var(--text2);font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:600;cursor:pointer;transition:all .2s;text-align:center}
.role-btn.active{border-color:var(--acc);background:var(--acc-s);color:var(--acc2)}
.field{display:flex;flex-direction:column;gap:6px;margin-bottom:14px}
.field label{font-size:11px;font-weight:600;letter-spacing:.08em;text-transform:uppercase;color:var(--text2)}
.field input,.field select,.field textarea{background:var(--bg3);border:1px solid var(--border);border-radius:10px;padding:12px 14px;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;color:var(--text);outline:none;transition:border-color .2s,box-shadow .2s;width:100%}
.field input:focus,.field select:focus,.field textarea:focus{border-color:var(--acc);box-shadow:0 0 0 3px var(--acc-s)}
.field input::placeholder,.field textarea::placeholder{color:var(--text3)}
.field textarea{resize:vertical;min-height:72px}
.btn-p{width:100%;padding:14px;background:linear-gradient(135deg,var(--acc),var(--acc-dark,#1d4ed8));border:none;border-radius:10px;font-family:'Plus Jakarta Sans',sans-serif;font-size:14px;font-weight:700;color:#fff;cursor:pointer;transition:all .2s;box-shadow:0 4px 20px var(--acc-s);margin-top:4px}
.btn-p:hover{transform:translateY(-1px);filter:brightness(1.1)}
.btn-p:active{transform:none}
.demo-hint{margin-top:18px;background:var(--bg3);border:1px solid var(--border2);border-radius:10px;padding:14px;font-size:12px;color:var(--text2);line-height:1.7}
.demo-hint strong{color:var(--text);display:block;margin-bottom:3px}

/* ── APP ── */
#app{display:none;min-height:100vh;flex-direction:column}

/* TOPBAR */
.topbar{position:sticky;top:0;z-index:100;background:rgba(13,17,23,.92);backdrop-filter:blur(14px);border-bottom:1px solid var(--border2);padding:0 16px;height:58px;display:flex;align-items:center;justify-content:space-between}
.tb-left{display:flex;align-items:center;gap:10px}
.tb-logo{font-family:'Syne',sans-serif;font-size:18px;font-weight:800}
.tb-logo span{color:var(--acc2)}
.tb-badge{background:var(--acc-s);color:var(--acc2);font-size:11px;font-weight:600;padding:3px 9px;border-radius:20px;border:1px solid rgba(99,179,237,.2)}
.tb-right{display:flex;align-items:center;gap:8px}
.avatar{width:34px;height:34px;border-radius:50%;background:linear-gradient(135deg,var(--acc),var(--purple));display:flex;align-items:center;justify-content:center;font-size:13px;font-weight:700;color:#fff;flex-shrink:0}
.logout-btn{background:none;border:1px solid var(--border);border-radius:8px;padding:6px 11px;font-family:'Plus Jakarta Sans',sans-serif;font-size:12px;color:var(--text2);cursor:pointer;transition:all .2s}
.logout-btn:hover{border-color:var(--red);color:var(--red)}

/* NAV */
.nav-tabs{display:flex;overflow-x:auto;gap:2px;padding:8px 12px;background:var(--bg2);border-bottom:1px solid var(--border2);scrollbar-width:none}
.nav-tabs::-webkit-scrollbar{display:none}
.nav-tab{flex-shrink:0;padding:8px 14px;border-radius:8px;border:none;background:transparent;color:var(--text2);font-family:'Plus Jakarta Sans',sans-serif;font-size:12px;font-weight:500;cursor:pointer;white-space:nowrap;transition:all .2s;display:flex;align-items:center;gap:5px}
.nav-tab.active{background:var(--acc-s);color:var(--acc2)}
.nav-tab:hover:not(.active){background:var(--bg3);color:var(--text)}

/* MAIN */
.main{flex:1;padding:16px;max-width:620px;margin:0 auto;width:100%}
.panel{display:none;animation:fadeUp .35s ease both}
.panel.active{display:block}

/* ── MYSTAT-STYLE CARDS ── */
.ms-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:16px}
.ms-card{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--radius);padding:16px;position:relative;overflow:hidden}
.ms-card::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(to right,var(--acc),var(--acc2))}
.ms-card.green::before{background:linear-gradient(to right,#16a34a,var(--green))}
.ms-card.orange::before{background:linear-gradient(to right,#d97706,var(--orange))}
.ms-card.purple::before{background:linear-gradient(to right,#7e22ce,var(--purple))}
.ms-card.red::before{background:linear-gradient(to right,#991b1b,var(--red))}
.ms-label{font-size:10px;color:var(--text2);font-weight:600;text-transform:uppercase;letter-spacing:.07em;margin-bottom:8px}
.ms-val{font-family:'Syne',sans-serif;font-size:30px;font-weight:800;line-height:1}
.ms-sub{font-size:11px;color:var(--text2);margin-top:5px}
.ms-card.blue .ms-val{color:var(--acc2)}
.ms-card.green .ms-val{color:var(--green)}
.ms-card.orange .ms-val{color:var(--orange)}
.ms-card.purple .ms-val{color:var(--purple)}
.ms-card.red .ms-val{color:var(--red)}

/* ── SECTION ── */
.sec-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:10px;margin-top:20px}
.sec-title{font-size:14px;font-weight:700}
.sec-btn{background:none;border:1px solid var(--border);border-radius:8px;padding:6px 12px;font-family:'Plus Jakarta Sans',sans-serif;font-size:12px;color:var(--text2);cursor:pointer;transition:all .2s}
.sec-btn:hover{border-color:var(--acc);color:var(--acc2)}

/* ── TASK / NOTICE CARDS ── */
.item-list{display:flex;flex-direction:column;gap:8px}
.item-card{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--radius);padding:15px;cursor:pointer;transition:all .2s}
.item-card:hover{border-color:var(--border);background:var(--bg3)}
.item-top{display:flex;align-items:flex-start;justify-content:space-between;gap:8px;margin-bottom:6px}
.item-title{font-size:13px;font-weight:600;line-height:1.35}
.item-sub{font-size:11px;color:var(--text2);margin-top:3px}
.item-meta{display:flex;align-items:center;gap:10px;flex-wrap:wrap;margin-top:6px}
.meta-c{font-size:11px;color:var(--text2);display:flex;align-items:center;gap:3px}

/* ── PROGRESS ── */
.prog-wrap{margin-top:10px}
.prog-lbl{display:flex;justify-content:space-between;font-size:10px;color:var(--text2);margin-bottom:4px}
.prog-bar{height:5px;background:var(--bg3);border-radius:3px;overflow:hidden}
.prog-fill{height:100%;border-radius:3px;transition:width 1s cubic-bezier(.22,.68,0,1.2)}
.prog-fill.b{background:linear-gradient(to right,var(--acc),var(--acc2))}
.prog-fill.g{background:linear-gradient(to right,#16a34a,var(--green))}
.prog-fill.o{background:linear-gradient(to right,#d97706,var(--orange))}
.prog-fill.r{background:linear-gradient(to right,#991b1b,var(--red))}

/* ── NOTICE CARD ── */
.notice-c{background:var(--bg2);border:1px solid var(--border2);border-left:3px solid var(--acc);border-radius:var(--radius);padding:14px;margin-bottom:8px}
.notice-c.month-winner{border-left-color:var(--orange)}
.n-head{display:flex;justify-content:space-between;align-items:center;margin-bottom:5px}
.n-title{font-size:13px;font-weight:600}
.n-date{font-size:11px;color:var(--text2)}
.n-body{font-size:12px;color:var(--text2);line-height:1.6}

/* ── LEADERBOARD ── */
.lb-item{display:flex;align-items:center;gap:12px;background:var(--bg2);border:1px solid var(--border2);border-radius:var(--radius);padding:13px 14px;margin-bottom:7px;transition:all .2s}
.lb-item:hover{border-color:var(--border)}
.lb-item.me{border-color:var(--acc)!important;background:var(--acc-s)!important}
.lb-rank{width:28px;height:28px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-family:'Syne',sans-serif;font-size:13px;font-weight:800;flex-shrink:0}
.lb-rank.r1{background:linear-gradient(135deg,#fbbf24,#f59e0b);color:#000}
.lb-rank.r2{background:linear-gradient(135deg,#94a3b8,#64748b);color:#fff}
.lb-rank.r3{background:linear-gradient(135deg,#d97706,#92400e);color:#fff}
.lb-rank.rn{background:var(--bg3);color:var(--text2);font-size:11px}
.lb-info{flex:1;min-width:0}
.lb-name{font-size:13px;font-weight:600;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.lb-detail{font-size:11px;color:var(--text2);margin-top:2px}
.lb-score{font-family:'Syne',sans-serif;font-size:20px;font-weight:800;color:var(--acc2);flex-shrink:0}

/* ── ATTENDANCE TABLE ── */
.att-table{width:100%;border-collapse:collapse;font-size:12px}
.att-table th{padding:9px 10px;text-align:left;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:.06em;color:var(--text2);border-bottom:1px solid var(--border2)}
.att-table td{padding:10px 10px;border-bottom:1px solid var(--border2);vertical-align:middle}
.att-table tr:last-child td{border-bottom:none}
.att-table tr:hover td{background:rgba(255,255,255,.015)}
.att-wrap{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--radius);overflow:hidden;margin-bottom:12px}
.att-btn{width:28px;height:28px;border-radius:6px;border:none;cursor:pointer;font-size:13px;transition:all .2s;display:inline-flex;align-items:center;justify-content:center}
.att-btn.present{background:var(--green-s);color:var(--green)}
.att-btn.absent{background:var(--red-s);color:var(--red)}
.att-btn.unset{background:var(--bg3);color:var(--text2)}
.att-btn:hover{filter:brightness(1.2)}

/* ── GRADE ROWS ── */
.grade-row{display:flex;align-items:center;gap:10px;background:var(--bg3);border:1px solid var(--border2);border-radius:10px;padding:10px 13px;margin-bottom:7px}
.grade-row .gname{flex:1;font-size:13px;font-weight:500;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.grade-row .gabsent{font-size:11px;color:var(--red);flex-shrink:0}
.grade-row input[type=number]{width:58px;padding:6px 8px;text-align:center;background:var(--bg2);border:1px solid var(--border);border-radius:8px;color:var(--text);font-size:13px;outline:none;font-family:'Plus Jakarta Sans',sans-serif}
.grade-row input[type=number]:focus{border-color:var(--acc)}

/* ── STUDENT LIST ── */
.stu-card{background:var(--bg2);border:1px solid var(--border2);border-radius:var(--radius);padding:13px 14px;margin-bottom:8px;display:flex;align-items:center;gap:12px;cursor:pointer;transition:all .2s}
.stu-card:hover{border-color:var(--border);background:var(--bg3)}
.stu-av{width:36px;height:36px;border-radius:10px;background:linear-gradient(135deg,var(--acc),var(--purple));display:flex;align-items:center;justify-content:center;font-weight:700;font-size:14px;color:#fff;flex-shrink:0}
.stu-info{flex:1;min-width:0}
.stu-name{font-size:13px;font-weight:600}
.stu-meta{font-size:11px;color:var(--text2);margin-top:2px}
.stu-score{font-family:'Syne',sans-serif;font-size:18px;font-weight:800;color:var(--acc2);flex-shrink:0}

/* ── MODAL ── */
.modal-ov{position:fixed;inset:0;z-index:200;background:rgba(0,0,0,.72);backdrop-filter:blur(5px);display:none;align-items:flex-end;justify-content:center;padding:0}
.modal-ov.open{display:flex}
.modal{background:var(--bg2);border:1px solid var(--border);border-radius:20px 20px 0 0;width:100%;max-width:520px;padding:24px 20px 32px;max-height:88vh;overflow-y:auto;animation:slideUp .3s cubic-bezier(.22,.68,0,1.2) both}
.m-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:20px}
.m-title{font-family:'Syne',sans-serif;font-size:18px;font-weight:800}
.m-close{background:var(--bg3);border:none;border-radius:8px;width:30px;height:30px;cursor:pointer;color:var(--text2);font-size:16px;display:flex;align-items:center;justify-content:center;transition:all .2s}
.m-close:hover{background:var(--red-s);color:var(--red)}
.m-footer{display:flex;gap:8px;margin-top:18px}
.btn-sec{flex:1;padding:12px;border-radius:10px;border:1px solid var(--border);background:transparent;color:var(--text2);cursor:pointer;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:600;transition:all .2s}
.btn-sec:hover{background:var(--bg3);color:var(--text)}
.btn-p-sm{padding:12px 20px;background:linear-gradient(135deg,var(--acc),var(--acc-dark,#1d4ed8));border:none;border-radius:10px;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;font-weight:700;color:#fff;cursor:pointer;transition:all .2s;white-space:nowrap}
.btn-p-sm:hover{filter:brightness(1.1)}

/* ── SEARCH ── */
.search-box{background:var(--bg2);border:1px solid var(--border);border-radius:10px;padding:10px 14px;font-family:'Plus Jakarta Sans',sans-serif;font-size:13px;color:var(--text);outline:none;width:100%;margin-bottom:12px;transition:border-color .2s}
.search-box:focus{border-color:var(--acc)}
.search-box::placeholder{color:var(--text3)}

/* ── TOAST ── */
.toast{position:fixed;bottom:24px;left:50%;transform:translateX(-50%) translateY(80px);background:var(--bg2);border:1px solid var(--border);border-radius:12px;padding:12px 20px;font-size:13px;font-weight:500;box-shadow:0 8px 32px rgba(0,0,0,.5);z-index:500;transition:transform .4s cubic-bezier(.22,.68,0,1.2),opacity .3s;opacity:0;white-space:nowrap}
.toast.show{transform:translateX(-50%) translateY(0);opacity:1}
.toast.green{border-color:var(--green);color:var(--green)}
.toast.red{border-color:var(--red);color:var(--red)}
.toast.blue{border-color:var(--acc);color:var(--acc2)}

/* ── MONTH WINNER BANNER ── */
.winner-banner{background:linear-gradient(135deg,rgba(245,158,11,.15),rgba(168,85,247,.12));border:1px solid rgba(245,158,11,.3);border-radius:var(--radius);padding:16px;margin-bottom:14px;text-align:center}
.winner-banner .trophy{font-size:28px;margin-bottom:6px}
.winner-banner .wtitle{font-family:'Syne',sans-serif;font-size:15px;font-weight:800;color:var(--orange);margin-bottom:4px}
.winner-banner .wsub{font-size:12px;color:var(--text2);line-height:1.6}

/* ── EMPTY ── */
.empty{text-align:center;padding:36px 16px;color:var(--text2)}
.empty-icon{font-size:36px;margin-bottom:10px;opacity:.5}
.empty-text{font-size:13px}

/* ── PARENT MSG ── */
.parent-row{background:var(--bg3);border:1px solid var(--border2);border-radius:10px;padding:12px 14px;margin-bottom:8px;display:flex;align-items:center;justify-content:space-between;gap:10px}
.parent-name{font-size:13px;font-weight:500}
.parent-num{font-size:12px;color:var(--text2)}
.msg-btn{background:var(--acc-s);border:1px solid rgba(99,179,237,.2);border-radius:8px;padding:7px 12px;font-size:12px;font-weight:600;color:var(--acc2);cursor:pointer;transition:all .2s;white-space:nowrap}
.msg-btn:hover{background:var(--acc);color:#fff}

/* ── ANIMATIONS ── */
@keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}
@keyframes slideUp{from{opacity:0;transform:translateY(50px)}to{opacity:1;transform:translateY(0)}}
.stagger>*{animation:fadeUp .4s ease both}
.stagger>*:nth-child(1){animation-delay:.04s}.stagger>*:nth-child(2){animation-delay:.08s}
.stagger>*:nth-child(3){animation-delay:.12s}.stagger>*:nth-child(4){animation-delay:.16s}
.stagger>*:nth-child(5){animation-delay:.20s}.stagger>*:nth-child(6){animation-delay:.24s}

/* ── TABS INSIDE PANEL ── */
.inner-tabs{display:flex;gap:4px;margin-bottom:14px;overflow-x:auto;scrollbar-width:none}
.inner-tabs::-webkit-scrollbar{display:none}
.inner-tab{flex-shrink:0;padding:7px 14px;border-radius:8px;border:1px solid var(--border2);background:transparent;color:var(--text2);font-size:12px;font-weight:500;cursor:pointer;transition:all .2s;font-family:'Plus Jakarta Sans',sans-serif}
.inner-tab.active{background:var(--acc-s);border-color:rgba(99,179,237,.25);color:var(--acc2)}

/* MONTH SELECTOR */
.month-sel{background:var(--bg2);border:1px solid var(--border);border-radius:8px;padding:7px 12px;font-size:12px;color:var(--text);outline:none;font-family:'Plus Jakarta Sans',sans-serif;cursor:pointer}
</style>
</head>
<body>

<!-- ══ LOGIN ══ -->
<div id="loginScreen">
  <div class="l-logo">
    <div class="l-logo-icon">📐</div>
    <div class="l-logo-text">Math<span>Class</span></div>
  </div>
  <div class="l-card">
    <div class="l-title">Xoş gəlmisiniz</div>
    <div class="l-sub">Sinif panelinə daxil olun</div>
    <div class="role-sw">
      <button class="role-btn active" id="rTeacher" onclick="setRole('teacher')">👩‍🏫 Müəllim</button>
      <button class="role-btn" id="rStudent" onclick="setRole('student')">🎓 Şagird</button>
    </div>
    <div class="field"><label>İstifadəçi adı</label><input id="lUser" type="text" placeholder="ad.soyad" value="muellim"/></div>
    <div class="field"><label>Şifrə</label><input id="lPass" type="password" placeholder="••••••" value="1234"/></div>
    <button class="btn-p" onclick="doLogin()">Daxil ol →</button>
    <div class="demo-hint">
      <strong>Demo giriş:</strong>
      Müəllim: <code>muellim / 1234</code><br>
      Şagird: <code>ayse / 1234</code> (və ya istənilən şagird adı)
    </div>
  </div>
</div>

<!-- ══ APP ══ -->
<div id="app">
  <div class="topbar">
    <div class="tb-left">
      <div class="tb-logo">Math<span>Class</span></div>
      <div class="tb-badge" id="roleBadge">Müəllim</div>
    </div>
    <div class="tb-right">
      <div class="avatar" id="userAvatar">M</div>
      <button class="logout-btn" onclick="doLogout()">Çıxış</button>
    </div>
  </div>
  <div class="nav-tabs" id="navTabs"></div>
  <div class="main" id="mainContent"></div>
</div>

<!-- ══ MODALS ══ -->
<!-- Add task -->
<div class="modal-ov" id="mTask">
  <div class="modal">
    <div class="m-head"><div class="m-title">Yeni Tapşırıq / Dərs</div><button class="m-close" onclick="closeM('mTask')">✕</button></div>
    <div class="field"><label>Dərs nömrəsi</label><input id="tLesson" type="number" placeholder="12" min="1"/></div>
    <div class="field"><label>Keçilən mövzu</label><input id="tTopic" type="text" placeholder="Kəsrlərin toplanması"/></div>
    <div class="field"><label>Ev tapşırığı (səhifə / məsələ)</label><input id="tHW" type="text" placeholder="s.45, məs. 3-8"/></div>
    <div class="field"><label>Qeyd / xəbərdarlıq</label><textarea id="tNote" placeholder="Şagirdlər üçün əlavə qeyd..."></textarea></div>
    <div class="field"><label>Tarix</label><input id="tDate" type="date"/></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mTask')">Ləğv</button>
      <button class="btn-p-sm" onclick="addTask()">Göndər</button>
    </div>
  </div>
</div>

<!-- Notice -->
<div class="modal-ov" id="mNotice">
  <div class="modal">
    <div class="m-head"><div class="m-title">Yeni Elan</div><button class="m-close" onclick="closeM('mNotice')">✕</button></div>
    <div class="field"><label>Başlıq</label><input id="nTitle" type="text" placeholder="Elan başlığı"/></div>
    <div class="field"><label>Məzmun</label><textarea id="nBody" placeholder="Elanın məzmunu..."></textarea></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mNotice')">Ləğv</button>
      <button class="btn-p-sm" onclick="addNotice()">Yayımla</button>
    </div>
  </div>
</div>

<!-- Add student -->
<div class="modal-ov" id="mAddStu">
  <div class="modal">
    <div class="m-head"><div class="m-title">Şagird Əlavə Et</div><button class="m-close" onclick="closeM('mAddStu')">✕</button></div>
    <div class="field"><label>Ad Soyad</label><input id="asName" type="text" placeholder="Aysel Hüseynova"/></div>
    <div class="field"><label>İstifadəçi adı</label><input id="asUser" type="text" placeholder="aysel.h"/></div>
    <div class="field"><label>Valideyn adı</label><input id="asParent" type="text" placeholder="Hüseyn Hüseynov"/></div>
    <div class="field"><label>Valideyn nömrəsi</label><input id="asPhone" type="tel" placeholder="+994 50 000 00 00"/></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mAddStu')">Ləğv</button>
      <button class="btn-p-sm" onclick="addStudent()">Əlavə Et</button>
    </div>
  </div>
</div>

<!-- Grade modal -->
<div class="modal-ov" id="mGrade">
  <div class="modal">
    <div class="m-head"><div class="m-title" id="mGradeTitle">Qiymətlər</div><button class="m-close" onclick="closeM('mGrade')">✕</button></div>
    <div id="mGradeBody"></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mGrade')">Bağla</button>
      <button class="btn-p-sm" onclick="saveGrades()">Saxla</button>
    </div>
  </div>
</div>

<!-- Attendance modal -->
<div class="modal-ov" id="mAtt">
  <div class="modal">
    <div class="m-head"><div class="m-title" id="mAttTitle">Davamiyyət</div><button class="m-close" onclick="closeM('mAtt')">✕</button></div>
    <div id="mAttBody"></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mAtt')">Bağla</button>
      <button class="btn-p-sm" onclick="saveAtt()">Saxla</button>
    </div>
  </div>
</div>

<!-- Parent message modal -->
<div class="modal-ov" id="mParent">
  <div class="modal">
    <div class="m-head"><div class="m-title" id="mParentTitle">Valideynə Mesaj</div><button class="m-close" onclick="closeM('mParent')">✕</button></div>
    <div id="mParentInfo" style="background:var(--bg3);border-radius:10px;padding:12px 14px;margin-bottom:14px;font-size:13px;color:var(--text2)"></div>
    <div class="field"><label>Mesaj</label><textarea id="parentMsg" placeholder="Valideynə yazacağınız mesajı daxil edin..."></textarea></div>
    <div class="m-footer">
      <button class="btn-sec" onclick="closeM('mParent')">Ləğv</button>
      <button class="btn-p-sm" onclick="sendParentMsg()">Göndər</button>
    </div>
  </div>
</div>

<!-- Student detail modal -->
<div class="modal-ov" id="mStuDetail">
  <div class="modal">
    <div class="m-head"><div class="m-title" id="sdName">Şagird</div><button class="m-close" onclick="closeM('mStuDetail')">✕</button></div>
    <div id="sdBody"></div>
  </div>
</div>

<!-- Toast -->
<div class="toast" id="toast"></div>

<script>
/* ════════════════════════════════════════
   DATA
════════════════════════════════════════ */
const MONTHS = ['Yanvar','Fevral','Mart','Aprel','May','İyun','İyul','Avqust','Sentyabr','Oktyabr','Noyabr','Dekabr'];
const NOW_MONTH = 4; // May (0-based)
const NOW_YEAR  = 2025;

// 30 students
const STUDENTS = [
  {id:1, name:'Aysel Hüseynova',   user:'ayse',    parent:'Hüseyn Hüseynov',   phone:'+994501234501'},
  {id:2, name:'Orxan Quliyev',     user:'orxan',   parent:'Qulu Quliyev',       phone:'+994512234502'},
  {id:3, name:'Nərmin Əliyeva',    user:'nermin',  parent:'Əli Əliyev',         phone:'+994701234503'},
  {id:4, name:'Tural Babayev',     user:'tural',   parent:'Baba Babayev',       phone:'+994551234504'},
  {id:5, name:'Günel Məmmədova',   user:'gunel',   parent:'Məmməd Məmmədov',    phone:'+994501234505'},
  {id:6, name:'Rauf İsmayılov',    user:'rauf',    parent:'İsmayıl İsmayılov',  phone:'+994512234506'},
  {id:7, name:'Sevinc Rzayeva',    user:'sevinc',  parent:'Rza Rzayev',         phone:'+994701234507'},
  {id:8, name:'Elnur Qəhrəmanov',  user:'elnur',   parent:'Qəhrəman Qəhrəmanov',phone:'+994551234508'},
  {id:9, name:'Leyla Əhmədova',    user:'leyla',   parent:'Əhməd Əhmədov',      phone:'+994501234509'},
  {id:10,name:'Kamran Nəsirov',    user:'kamran',  parent:'Nəsir Nəsirov',      phone:'+994512234510'},
  {id:11,name:'Zülfiyyə Həsənova', user:'zulfi',   parent:'Həsən Həsənov',      phone:'+994701234511'},
  {id:12,name:'Ülvü Cəfərov',      user:'ulvu',    parent:'Cəfər Cəfərov',      phone:'+994551234512'},
  {id:13,name:'Könül Sultanova',   user:'konul',   parent:'Sultan Sultanov',    phone:'+994501234513'},
  {id:14,name:'Anar Həsənli',      user:'anar',    parent:'Həsən Həsənli',      phone:'+994512234514'},
  {id:15,name:'Şəbnəm Rəhimova',   user:'sebnem',  parent:'Rəhim Rəhimov',      phone:'+994701234515'},
  {id:16,name:'Fərid Axundov',     user:'ferid',   parent:'Axund Axundov',      phone:'+994551234516'},
  {id:17,name:'Nigar Abbasova',    user:'nigar',   parent:'Abbas Abbasov',      phone:'+994501234517'},
  {id:18,name:'Vüsal Hümbətov',    user:'vusal',   parent:'Hümbət Hümbətov',    phone:'+994512234518'},
  {id:19,name:'Aytən Musayeva',    user:'ayten',   parent:'Musa Musayev',       phone:'+994701234519'},
  {id:20,name:'Ramil Kərimov',     user:'ramil',   parent:'Kərim Kərimov',      phone:'+994551234520'},
  {id:21,name:'Samirə Mirzəyeva',  user:'samire',  parent:'Mirzə Mirzəyev',     phone:'+994501234521'},
  {id:22,name:'Rəşad Əliyev',      user:'resad',   parent:'Əli Əliyev 2',       phone:'+994512234522'},
  {id:23,name:'Xədicə Yusifova',   user:'xedice',  parent:'Yusif Yusifov',      phone:'+994701234523'},
  {id:24,name:'Murad Cavadov',     user:'murad',   parent:'Cavad Cavadov',      phone:'+994551234524'},
  {id:25,name:'Türkan Novruzova',  user:'turkan',  parent:'Novruz Novruzov',    phone:'+994501234525'},
  {id:26,name:'Elçin Qasımov',     user:'elcin',   parent:'Qasım Qasımov',      phone:'+994512234526'},
  {id:27,name:'Afət İbrahimova',   user:'afet',    parent:'İbrahim İbrahimov',  phone:'+994701234527'},
  {id:28,name:'Ceyhun Məmişov',    user:'ceyhun',  parent:'Məmiş Məmişov',      phone:'+994551234528'},
  {id:29,name:'Lalə Qurbanova',    user:'lale',    parent:'Qurban Qurbanov',    phone:'+994501234529'},
  {id:30,name:'Emil Paşayev',      user:'emil',    parent:'Paşa Paşayev',       phone:'+994512234530'},
];

// tasks: {id, lesson, topic, hw, note, date, month}
let tasks = [
  {id:1,lesson:1,topic:'Tam ədədlər — Giriş',        hw:'s.12, məs.1-5',  note:'Riyaziyyat dəftərini gətirin.',    date:'2025-04-01',month:3},
  {id:2,lesson:2,topic:'Toplama və çıxma',            hw:'s.18, məs.6-12', note:'',                                  date:'2025-04-03',month:3},
  {id:3,lesson:3,topic:'Vurma cədvəlinin təkrarı',   hw:'s.22, məs.1-10', note:'Test hazırlığı üçün təkrar edin.', date:'2025-04-08',month:3},
  {id:4,lesson:4,topic:'Kəsrlər — Anlayış',          hw:'s.30, məs.3-8',  note:'',                                  date:'2025-04-10',month:3},
  {id:5,lesson:5,topic:'Kəsrlərin toplanması',        hw:'s.35, məs.1-6',  note:'Çətin məsələlər üçün kömək istəyin.',date:'2025-04-15',month:3},
  {id:6,lesson:6,topic:'Faizlər',                     hw:'s.40, məs.5-10', note:'',                                  date:'2025-04-22',month:3},
  {id:7,lesson:7,topic:'Tənliklər — Giriş',          hw:'s.48, məs.2-7',  note:'Sinifdə yoxlanılacaq.',            date:'2025-05-01',month:4},
  {id:8,lesson:8,topic:'Həndəsə — Sahə hesabı',      hw:'s.55, məs.1-5',  note:'Cetvel gətirin.',                  date:'2025-05-06',month:4},
];
let taskSeq = 9;

// grades[month][taskId][studentId] = 0-10
let grades = {};
(function initGrades(){
  [3,4].forEach(m=>{
    grades[m]={};
    tasks.filter(t=>t.month===m).forEach(t=>{
      grades[m][t.id]={};
      STUDENTS.forEach(s=>{
        if(m===3) grades[m][t.id][s.id]=Math.max(0,Math.min(10,Math.round(5+Math.random()*5+(s.id%3))));
        else if(t.id<=8) grades[m][t.id][s.id]=Math.max(0,Math.min(10,Math.round(5+Math.random()*5+(s.id%3))));
      });
    });
  });
})();

// attendance[taskId][studentId] = 'present'|'absent'|null
let attendance = {};
(function initAtt(){
  tasks.forEach(t=>{
    attendance[t.id]={};
    STUDENTS.forEach(s=>{
      attendance[t.id][s.id] = Math.random()<0.9 ? 'present' : 'absent';
    });
  });
})();

// notices
let notices = [
  {id:1,title:'İmtahan tarixi — 20 May',body:'Yarımillik yoxlama işi 20 may tarixindədir. Mövzular: Kəsrlər, Faizlər, Tənliklər.',date:'6 may',month:4},
  {id:2,title:'Növbəti dərs — Həndəsə',body:'Cümə dərsinə cətvel və pergel gətirin.',date:'5 may',month:4},
];
let noticeSeq = 3;

/* ════════════════════════════════════════
   AUTH & STATE
════════════════════════════════════════ */
let role = 'teacher';
let currentSid = null;
let gradingTaskId = null;
let attTaskId = null;
let parentMsgSid = null;
let activePanel = '';
let selectedMonth = NOW_MONTH;

function setRole(r){
  role=r;
  document.getElementById('rTeacher').classList.toggle('active',r==='teacher');
  document.getElementById('rStudent').classList.toggle('active',r==='student');
  document.getElementById('lUser').value = r==='teacher'?'muellim':'ayse';
}

function doLogin(){
  const u=document.getElementById('lUser').value.trim();
  const p=document.getElementById('lPass').value.trim();
  if(!u||!p){showToast('Məlumatları daxil edin','');return;}
  if(role==='teacher'){
    if(u==='muellim'&&p==='1234'){launchApp('teacher',null);}
    else showToast('Yanlış giriş','');
  } else {
    const s=STUDENTS.find(x=>x.user===u);
    if(s&&p==='1234'){currentSid=s.id;launchApp('student',s);}
    else showToast('Yanlış giriş','');
  }
}

function doLogout(){
  document.getElementById('app').style.display='none';
  document.getElementById('loginScreen').style.display='flex';
  currentSid=null;
}

/* ════════════════════════════════════════
   THEME
════════════════════════════════════════ */
function applyTheme(r){
  const root=document.documentElement.style;
  if(r==='teacher'){
    root.setProperty('--acc','#e8243b');
    root.setProperty('--acc2','#ff5567');
    root.setProperty('--acc-s','rgba(232,36,59,.13)');
    root.setProperty('--acc-dark','#8b0e1c');
  } else {
    root.setProperty('--acc','#3b82f6');
    root.setProperty('--acc2','#60a5fa');
    root.setProperty('--acc-s','rgba(59,130,246,.13)');
    root.setProperty('--acc-dark','#1d4ed8');
  }
}

/* ════════════════════════════════════════
   LAUNCH
════════════════════════════════════════ */
function launchApp(r,stu){
  applyTheme(r);
  document.getElementById('loginScreen').style.display='none';
  const app=document.getElementById('app');
  app.style.display='flex';
  document.getElementById('roleBadge').textContent=r==='teacher'?'Müəllim':'Şagird';
  document.getElementById('userAvatar').textContent=r==='teacher'?'M':stu.name[0];
  buildNav(r);
}

function buildNav(r){
  const tabs=document.getElementById('navTabs');
  tabs.innerHTML='';
  const defs = r==='teacher' ? [
    {id:'dash',  label:'📊 Panel'},
    {id:'tasks', label:'📋 Tapşırıqlar'},
    {id:'att',   label:'📅 Davamiyyət'},
    {id:'grades',label:'✏️ Qiymət'},
    {id:'stus',  label:'👥 Şagirdlər'},
    {id:'parent',label:'📱 Valideyn'},
    {id:'notices',label:'📢 Elanlar'},
  ] : [
    {id:'sdash',  label:'🏠 Panel'},
    {id:'stasks', label:'📚 Tapşırıqlar'},
    {id:'sresults',label:'📈 Qiymətlər'},
    {id:'slead',  label:'🏆 Liderboard'},
    {id:'satt',   label:'📅 Davamiyyət'},
  ];
  defs.forEach((d,i)=>{
    const b=document.createElement('button');
    b.className='nav-tab'+(i===0?' active':'');
    b.textContent=d.label;
    b.onclick=()=>{
      document.querySelectorAll('.nav-tab').forEach(x=>x.classList.remove('active'));
      b.classList.add('active');
      renderPanel(d.id);
    };
    tabs.appendChild(b);
  });
  renderPanel(defs[0].id);
}

function renderPanel(id){
  activePanel=id;
  const mc=document.getElementById('mainContent');
  mc.innerHTML='<div class="panel active" id="dynPanel"></div>';
  const p=document.getElementById('dynPanel');
  const fn={
    dash:renderDash, tasks:renderTasks, att:renderAttPanel,
    grades:renderGradesPanel, stus:renderStudents,
    parent:renderParentPanel, notices:renderNotices,
    sdash:renderSDash, stasks:renderSTasks,
    sresults:renderSResults, slead:renderSLead, satt:renderSAtt,
  }[id];
  if(fn) fn(p);
}

/* ════════════════════════════════════════
   HELPERS
════════════════════════════════════════ */
function stuAvg(sid,month){
  const mTasks=tasks.filter(t=>t.month===month);
  const scores=mTasks.map(t=>(grades[month]?.[t.id]?.[sid]??null)).filter(x=>x!==null);
  return scores.length ? +(scores.reduce((a,b)=>a+b,0)/scores.length).toFixed(1) : null;
}
function overallAvg(sid){
  const all=[];
  Object.keys(grades).forEach(m=>{
    tasks.filter(t=>t.month==m).forEach(t=>{
      const g=grades[m]?.[t.id]?.[sid];
      if(g!=null) all.push(g);
    });
  });
  return all.length ? +(all.reduce((a,b)=>a+b,0)/all.length).toFixed(1) : null;
}
function stuAbsent(sid){
  let c=0;
  Object.values(attendance).forEach(d=>{ if(d[sid]==='absent') c++; });
  return c;
}
function stuAttPct(sid){
  const total=Object.keys(attendance).length;
  if(!total) return 100;
  const present=Object.values(attendance).filter(d=>d[sid]==='present').length;
  return Math.round(present/total*100);
}
function rankStudents(month){
  return STUDENTS.slice().sort((a,b)=>{
    const aa=stuAvg(a.id,month)??-1, bb=stuAvg(b.id,month)??-1;
    return bb-aa;
  });
}
function todayStr(){
  const d=new Date();
  return d.getDate()+' '+MONTHS[d.getMonth()].toLowerCase().slice(0,3);
}
function scoreColor(v){return v>=8?'g':v>=6?'b':v>=4?'o':'r'}
function pctFill(p){return p>=80?'g':p>=60?'b':p>=40?'o':'r'}

/* ════════════════════════════════════════
   TEACHER — DASHBOARD
════════════════════════════════════════ */
function renderDash(p){
  const totalAbs=STUDENTS.reduce((s,st)=>s+stuAbsent(st.id),0);
  const avgs=STUDENTS.map(s=>overallAvg(s.id)).filter(x=>x!==null);
  const classAvg=avgs.length?(avgs.reduce((a,b)=>a+b,0)/avgs.length).toFixed(1):'—';
  const monthTasks=tasks.filter(t=>t.month===NOW_MONTH);

  // month winners for banner
  const ranked=rankStudents(NOW_MONTH);
  const top3=ranked.slice(0,3).filter(s=>stuAvg(s.id,NOW_MONTH)!==null);

  p.innerHTML=`
  <div class="ms-grid stagger">
    <div class="ms-card blue"><div class="ms-label">Şagirdlər</div><div class="ms-val">${STUDENTS.length}</div><div class="ms-sub">aktiv sinif</div></div>
    <div class="ms-card green"><div class="ms-label">Sinif orta</div><div class="ms-val">${classAvg}</div><div class="ms-sub">10 üzərindən</div></div>
    <div class="ms-card red"><div class="ms-label">Qayiblər</div><div class="ms-val">${totalAbs}</div><div class="ms-sub">ümumi dərs</div></div>
    <div class="ms-card purple"><div class="ms-label">Bu ay tapşırıq</div><div class="ms-val">${monthTasks.length}</div><div class="ms-sub">${MONTHS[NOW_MONTH]} ${NOW_YEAR}</div></div>
  </div>

  ${top3.length?`<div class="winner-banner">
    <div class="trophy">🏆</div>
    <div class="wtitle">${MONTHS[NOW_MONTH-1]} Ayının Qalibləri</div>
    <div class="wsub">${top3.map((s,i)=>`${i+1}. ${s.name} — ${stuAvg(s.id,NOW_MONTH-1)??'—'}/10`).join('<br>')}</div>
  </div>`:''}

  <div class="sec-head" style="margin-top:8px"><div class="sec-title">Son tapşırıqlar</div><button class="sec-btn" onclick="openM('mTask')">+ Yeni</button></div>
  <div class="item-list stagger" id="dashTaskList"></div>
  `;

  const tl=document.getElementById('dashTaskList');
  tasks.slice(-4).reverse().forEach(t=>{
    const mGrades=grades[t.month]?.[t.id]||{};
    const vals=Object.values(mGrades);
    const avg=vals.length?(vals.reduce((a,b)=>a+b,0)/vals.length).toFixed(1):'—';
    const absCount=STUDENTS.filter(s=>attendance[t.id]?.[s.id]==='absent').length;
    tl.innerHTML+=`<div class="item-card">
      <div class="item-top">
        <div><div class="item-title">Dərs ${t.lesson} — ${t.topic}</div><div class="item-sub">📚 EV: ${t.hw}</div></div>
        <span class="badge g">⌀ ${avg}</span>
      </div>
      <div class="item-meta">
        <div class="meta-c">📅 ${t.date}</div>
        <div class="meta-c">❌ ${absCount} qayib</div>
      </div>
    </div>`;
  });
}

/* ════════════════════════════════════════
   TEACHER — TASKS
════════════════════════════════════════ */
function renderTasks(p){
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Bütün Tapşırıqlar</div><button class="sec-btn" onclick="openM('mTask')">+ Yeni tapşırıq</button></div>
  <div class="item-list stagger" id="taskListEl"></div>`;
  const el=document.getElementById('taskListEl');
  tasks.slice().reverse().forEach(t=>{
    const mG=grades[t.month]?.[t.id]||{};
    const vals=Object.values(mG);
    const avg=vals.length?(vals.reduce((a,b)=>a+b,0)/vals.length).toFixed(1):'—';
    const absC=STUDENTS.filter(s=>attendance[t.id]?.[s.id]==='absent').length;
    const gradedC=vals.length;
    el.innerHTML+=`<div class="item-card">
      <div class="item-top">
        <div>
          <div class="item-title">Dərs ${t.lesson} — ${t.topic}</div>
          <div class="item-sub">📚 ${t.hw}${t.note?` · 📝 ${t.note}`:''}</div>
        </div>
        <span class="badge ${avg!=='—'?'g':'o'}">${avg!=='—'?avg+'/10':'Qiymət yox'}</span>
      </div>
      <div class="item-meta">
        <div class="meta-c">📅 ${t.date}</div>
        <div class="meta-c">❌ ${absC} qayib</div>
        <div class="meta-c">✏️ ${gradedC}/${STUDENTS.length} qiymət</div>
      </div>
      <div style="display:flex;gap:8px;margin-top:10px">
        <button class="inner-tab active" onclick="openGradeModal(${t.id})">Qiymət ver</button>
        <button class="inner-tab active" onclick="openAttModal(${t.id})">Davamiyyət</button>
      </div>
    </div>`;
  });
}

/* ════════════════════════════════════════
   TEACHER — ATTENDANCE PANEL
════════════════════════════════════════ */
function renderAttPanel(p){
  const monthTasks=tasks.slice().reverse();
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Davamiyyət Cədvəli</div></div>
  <div class="att-wrap">
  <table class="att-table">
  <thead><tr><th>Şagird</th>${monthTasks.map(t=>`<th style="text-align:center">D${t.lesson}</th>`).join('')}<th>%</th></tr></thead>
  <tbody id="attBody"></tbody>
  </table></div>`;
  const body=document.getElementById('attBody');
  STUDENTS.forEach(s=>{
    const cells=monthTasks.map(t=>{
      const st=attendance[t.id]?.[s.id]||'unset';
      const em=st==='present'?'✓':st==='absent'?'✗':'·';
      const cl=st==='present'?'g':st==='absent'?'r':'';
      return `<td style="text-align:center"><span class="badge ${cl}" style="min-width:22px">${em}</span></td>`;
    }).join('');
    const pct=stuAttPct(s.id);
    body.innerHTML+=`<tr>
      <td style="font-weight:500;white-space:nowrap;font-size:12px">${s.name}</td>
      ${cells}
      <td><span class="badge ${pctFill(pct)}">${pct}%</span></td>
    </tr>`;
  });
}

/* ════════════════════════════════════════
   TEACHER — GRADES PANEL
════════════════════════════════════════ */
function renderGradesPanel(p){
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Qiymət Paneli</div>
  <select class="month-sel" id="monthSelG" onchange="refreshGradePanel()">
    ${[3,4].map(m=>`<option value="${m}" ${m===NOW_MONTH?'selected':''}>${MONTHS[m]} ${NOW_YEAR}</option>`).join('')}
  </select></div>
  <div id="gradePanelBody"></div>`;
  refreshGradePanel();
}

function refreshGradePanel(){
  const m=parseInt(document.getElementById('monthSelG')?.value||NOW_MONTH);
  const mTasks=tasks.filter(t=>t.month===m);
  const body=document.getElementById('gradePanelBody');
  if(!body) return;
  if(!mTasks.length){body.innerHTML='<div class="empty"><div class="empty-icon">📭</div><div class="empty-text">Bu ayda tapşırıq yoxdur</div></div>';return;}
  body.innerHTML=mTasks.map(t=>{
    const vals=Object.values(grades[m]?.[t.id]||{});
    const avg=vals.length?(vals.reduce((a,b)=>a+b,0)/vals.length).toFixed(1):'—';
    return `<div class="item-card" style="margin-bottom:8px" onclick="openGradeModal(${t.id})">
      <div class="item-top">
        <div><div class="item-title">Dərs ${t.lesson} — ${t.topic}</div><div class="item-sub">${t.date}</div></div>
        <span class="badge g">⌀ ${avg}</span>
      </div>
      <div class="item-meta"><div class="meta-c">✏️ ${vals.length}/${STUDENTS.length} qiymət</div></div>
    </div>`;
  }).join('');
}

/* ════════════════════════════════════════
   TEACHER — STUDENTS
════════════════════════════════════════ */
function renderStudents(p){
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Şagird Siyahısı</div><button class="sec-btn" onclick="openM('mAddStu')">+ Əlavə et</button></div>
  <input class="search-box" placeholder="🔍 Ad ilə axtar..." oninput="filterStudents(this.value)"/>
  <div id="stuListEl"></div>`;
  renderStuList(STUDENTS);
}

function renderStuList(list){
  const el=document.getElementById('stuListEl');
  if(!el) return;
  const ranked=rankStudents(NOW_MONTH);
  el.innerHTML=list.map(s=>{
    const avg=overallAvg(s.id);
    const abs=stuAbsent(s.id);
    const rank=ranked.findIndex(x=>x.id===s.id)+1;
    return `<div class="stu-card" onclick="openStuDetail(${s.id})">
      <div class="stu-av">${s.name[0]}</div>
      <div class="stu-info">
        <div class="stu-name">${s.name}</div>
        <div class="stu-meta">Reytinq: ${rank}. · Qayib: ${abs} dərs · İştirak: ${stuAttPct(s.id)}%</div>
      </div>
      <div class="stu-score">${avg!==null?avg:'—'}</div>
    </div>`;
  }).join('');
}

function filterStudents(q){
  const list=STUDENTS.filter(s=>s.name.toLowerCase().includes(q.toLowerCase()));
  renderStuList(list);
}

/* ════════════════════════════════════════
   TEACHER — PARENT
════════════════════════════════════════ */
function renderParentPanel(p){
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Valideyn Əlaqə</div></div>
  <input class="search-box" placeholder="🔍 Şagird adı axtar..." oninput="filterParent(this.value)"/>
  <div id="parentListEl"></div>`;
  renderParentList(STUDENTS);
}

function renderParentList(list){
  const el=document.getElementById('parentListEl');
  if(!el) return;
  el.innerHTML=list.map(s=>`
    <div class="parent-row">
      <div>
        <div class="parent-name">${s.name}</div>
        <div class="parent-num">👤 ${s.parent} · 📞 ${s.phone}</div>
      </div>
      <button class="msg-btn" onclick="openParentMsg(${s.id})">Mesaj Yaz</button>
    </div>`).join('');
}

function filterParent(q){
  renderParentList(STUDENTS.filter(s=>s.name.toLowerCase().includes(q.toLowerCase())));
}

/* ════════════════════════════════════════
   TEACHER — NOTICES
════════════════════════════════════════ */
function renderNotices(p){
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Elanlar</div><button class="sec-btn" onclick="openM('mNotice')">+ Yeni elan</button></div>
  <div id="noticeListEl"></div>`;
  rebuildNotices();
}

function rebuildNotices(){
  const el=document.getElementById('noticeListEl');
  if(!el) return;
  if(!notices.length){el.innerHTML='<div class="empty"><div class="empty-icon">📢</div><div class="empty-text">Elan yoxdur</div></div>';return;}
  el.innerHTML=notices.slice().reverse().map(n=>`
    <div class="notice-c${n.winner?' month-winner':''}">
      <div class="n-head"><div class="n-title">${n.winner?'🏆 ':''} ${n.title}</div><div class="n-date">${n.date}</div></div>
      <div class="n-body">${n.body}</div>
    </div>`).join('');
}

/* ════════════════════════════════════════
   STUDENT — DASH
════════════════════════════════════════ */
function renderSDash(p){
  const sid=currentSid;
  const avg=overallAvg(sid);
  const ranked=rankStudents(NOW_MONTH);
  const rank=ranked.findIndex(s=>s.id===sid)+1;
  const abs=stuAbsent(sid);
  const attPct=stuAttPct(sid);
  const absPenalty=abs; // 1 xal per absence counted in rank display

  p.innerHTML=`
  <div class="ms-grid stagger">
    <div class="ms-card blue"><div class="ms-label">Orta Balım</div><div class="ms-val">${avg!==null?avg:'—'}</div><div class="ms-sub">10 üzərindən</div></div>
    <div class="ms-card green"><div class="ms-label">Reytinq</div><div class="ms-val">${rank?rank+'.':'—'}</div><div class="ms-sub">${STUDENTS.length} nəfər arasında</div></div>
    <div class="ms-card red"><div class="ms-label">Qayiblər</div><div class="ms-val">${abs}</div><div class="ms-sub">−${absPenalty} xal cəzası</div></div>
    <div class="ms-card purple"><div class="ms-label">İştirak</div><div class="ms-val">${attPct}%</div><div class="ms-sub">dərslərə</div></div>
  </div>
  <div class="sec-head"><div class="sec-title">📢 Elanlar</div></div>
  <div>${notices.slice().reverse().map(n=>`
    <div class="notice-c${n.winner?' month-winner':''}">
      <div class="n-head"><div class="n-title">${n.winner?'🏆 ':''} ${n.title}</div><div class="n-date">${n.date}</div></div>
      <div class="n-body">${n.body}</div>
    </div>`).join('') || '<div class="empty"><div class="empty-icon">📢</div><div class="empty-text">Elan yoxdur</div></div>'}</div>`;
}

/* ════════════════════════════════════════
   STUDENT — TASKS
════════════════════════════════════════ */
function renderSTasks(p){
  const sid=currentSid;
  p.innerHTML=`<div class="sec-head"><div class="sec-title">Tapşırıqlarım</div></div><div class="item-list stagger" id="sTaskListEl"></div>`;
  const el=document.getElementById('sTaskListEl');
  tasks.slice().reverse().forEach(t=>{
    const g=grades[t.month]?.[t.id]?.[sid];
    const att=attendance[t.id]?.[sid];
    const scored=g!==undefined;
    el.innerHTML+=`<div class="item-card">
      <div class="item-top">
        <div>
          <div class="item-title">Dərs ${t.lesson} — ${t.topic}</div>
          <div class="item-sub">📚 EV: ${t.hw}${t.note?`<br>📝 ${t.note}`:''}</div>
        </div>
        <span class="badge ${scored?scoreColor(g):'o'}">${scored?g+'/10':'Gözlənir'}</span>
      </div>
      <div class="item-meta">
        <div class="meta-c">📅 ${t.date}</div>
        <div class="meta-c">${att==='present'?'✅ İştirak etdi':att==='absent'?'❌ Qayib':'—'}</div>
      </div>
    </div>`;
  });
}

/* ════════════════════════════════════════
   STUDENT — RESULTS
════════════════════════════════════════ */
function renderSResults(p){
  const sid=currentSid;
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">Qiymətlərim</div>
  <select class="month-sel" onchange="this.closest('.panel').dataset.m=this.value;renderSResults(document.getElementById('dynPanel'))" >
    ${[3,4].map(m=>`<option value="${m}" ${m===NOW_MONTH?'selected':''}>${MONTHS[m]}</option>`).join('')}
  </select></div>
  <div class="att-wrap"><table class="att-table">
  <thead><tr><th>Tapşırıq</th><th>Mövzu</th><th style="text-align:center">Bal</th><th style="text-align:center">İştirak</th></tr></thead>
  <tbody id="sResBody"></tbody></table></div>`;
  const selM=p.dataset.m?parseInt(p.dataset.m):NOW_MONTH;
  const body=document.getElementById('sResBody');
  const mTasks=tasks.filter(t=>t.month===selM);
  mTasks.forEach(t=>{
    const g=grades[selM]?.[t.id]?.[sid];
    const att=attendance[t.id]?.[sid];
    const scored=g!==undefined;
    body.innerHTML+=`<tr>
      <td>D${t.lesson}</td>
      <td style="font-size:11px">${t.topic}</td>
      <td style="text-align:center"><span class="badge ${scored?scoreColor(g):'o'}">${scored?g:'-'}</span></td>
      <td style="text-align:center">${att==='present'?'✅':att==='absent'?'❌':'—'}</td>
    </tr>`;
  });
  if(!mTasks.length) body.innerHTML='<tr><td colspan="4" style="text-align:center;padding:20px;color:var(--text2)">Bu ayda tapşırıq yoxdur</td></tr>';
}

/* ════════════════════════════════════════
   STUDENT — LEADERBOARD
════════════════════════════════════════ */
function renderSLead(p){
  const sid=currentSid;
  p.innerHTML=`
  <div class="sec-head"><div class="sec-title">🏆 Liderboard</div>
  <select class="month-sel" onchange="this.dataset.m=this.value;refreshSLead(parseInt(this.value))">
    ${[3,4].map(m=>`<option value="${m}" ${m===NOW_MONTH?'selected':''}>${MONTHS[m]}</option>`).join('')}
  </select></div>
  <div id="lbEl"></div>`;
  refreshSLead(NOW_MONTH);
}

function refreshSLead(month){
  const sid=currentSid;
  const el=document.getElementById('lbEl');
  if(!el) return;
  const ranked=rankStudents(month);
  el.innerHTML=ranked.map((s,i)=>{
    const avg=stuAvg(s.id,month);
    const abs=stuAbsent(s.id);
    const score=avg!==null?Math.max(0,+(avg-abs*0.1).toFixed(1)):null; // abs penalty in display
    const isMe=s.id===sid;
    const rnkC=i===0?'r1':i===1?'r2':i===2?'r3':'rn';
    return `<div class="lb-item${isMe?' me':''}">
      <div class="lb-rank ${rnkC}">${i===0?'🥇':i===1?'🥈':i===2?'🥉':i+1}</div>
      <div class="lb-info">
        <div class="lb-name">${s.name}${isMe?' <span style="font-size:10px;color:var(--acc2)">(Sən)</span>':''}</div>
        <div class="lb-detail">⌀ ${avg??'—'}/10 · ❌ ${abs} qayib</div>
      </div>
      <div class="lb-score">${score!==null?score:'—'}</div>
    </div>`;
  }).join('');
}

/* ════════════════════════════════════════
   STUDENT — ATTENDANCE
════════════════════════════════════════ */
function renderSAtt(p){
  const sid=currentSid;
  const attPct=stuAttPct(sid);
  const abs=stuAbsent(sid);
  const present=Object.values(attendance).filter(d=>d[sid]==='present').length;
  p.innerHTML=`
  <div class="ms-grid" style="margin-bottom:16px">
    <div class="ms-card green"><div class="ms-label">İştirak</div><div class="ms-val">${present}</div><div class="ms-sub">dərs</div></div>
    <div class="ms-card red"><div class="ms-label">Qayib</div><div class="ms-val">${abs}</div><div class="ms-sub">dərs (−${abs} xal)</div></div>
  </div>
  <div class="prog-wrap" style="margin-bottom:20px">
    <div class="prog-lbl"><span>İştirak faizi</span><span>${attPct}%</span></div>
    <div class="prog-bar" style="height:8px"><div class="prog-fill ${pctFill(attPct)}" style="width:${attPct}%"></div></div>
  </div>
  <div class="sec-head"><div class="sec-title">Dərs Tarixçəsi</div></div>
  <div class="item-list">
  ${tasks.slice().reverse().map(t=>{
    const st=attendance[t.id]?.[sid];
    return `<div class="item-card" style="cursor:default">
      <div class="item-top">
        <div><div class="item-title">Dərs ${t.lesson} — ${t.topic}</div><div class="item-sub">${t.date}</div></div>
        <span class="badge ${st==='present'?'g':st==='absent'?'r':'o'}">${st==='present'?'✅ İştirak':st==='absent'?'❌ Qayib':'—'}</span>
      </div>
    </div>`;
  }).join('')}
  </div>`;
}

/* ════════════════════════════════════════
   MODAL — GRADE
════════════════════════════════════════ */
function openGradeModal(tid){
  gradingTaskId=tid;
  const t=tasks.find(x=>x.id===tid);
  document.getElementById('mGradeTitle').textContent=`Dərs ${t.lesson} — Qiymət`;
  const body=document.getElementById('mGradeBody');
  const m=t.month;
  body.innerHTML=STUDENTS.map(s=>{
    const existing=(grades[m]?.[tid]||{})[s.id]??'';
    const abs=attendance[tid]?.[s.id]==='absent';
    return `<div class="grade-row">
      <div class="gname">${s.name}</div>
      ${abs?'<span class="gabsent">❌ Qayib</span>':''}
      <input type="number" id="gr_${s.id}" min="0" max="10" step="0.5" value="${existing}" placeholder="—"/>
      <span style="font-size:11px;color:var(--text2)">/10</span>
    </div>`;
  }).join('');
  openM('mGrade');
}

function saveGrades(){
  const t=tasks.find(x=>x.id===gradingTaskId);
  if(!t) return;
  const m=t.month;
  if(!grades[m]) grades[m]={};
  if(!grades[m][gradingTaskId]) grades[m][gradingTaskId]={};
  STUDENTS.forEach(s=>{
    const inp=document.getElementById('gr_'+s.id);
    if(inp&&inp.value!=='') grades[m][gradingTaskId][s.id]=parseFloat(inp.value);
  });
  closeM('mGrade');
  showToast('✓ Qiymətlər saxlanıldı','green');
  if(activePanel==='grades') renderPanel('grades');
  if(activePanel==='tasks')  renderPanel('tasks');
}

/* ════════════════════════════════════════
   MODAL — ATTENDANCE
════════════════════════════════════════ */
function openAttModal(tid){
  attTaskId=tid;
  const t=tasks.find(x=>x.id===tid);
  document.getElementById('mAttTitle').textContent=`Dərs ${t.lesson} — Davamiyyət`;
  const body=document.getElementById('mAttBody');
  if(!attendance[tid]) attendance[tid]={};
  body.innerHTML=STUDENTS.map(s=>{
    const st=attendance[tid][s.id]||'unset';
    return `<div class="grade-row" id="arow_${s.id}">
      <div class="gname">${s.name}</div>
      <button class="att-btn present" onclick="toggleAtt(${tid},${s.id},'present')" id="abtn_p_${s.id}" style="${st==='present'?'opacity:1':'opacity:.35'}">✓</button>
      <button class="att-btn absent" onclick="toggleAtt(${tid},${s.id},'absent')" id="abtn_a_${s.id}" style="${st==='absent'?'opacity:1':'opacity:.35'}">✗</button>
    </div>`;
  }).join('');
  openM('mAtt');
}

function toggleAtt(tid,sid,val){
  if(!attendance[tid]) attendance[tid]={};
  attendance[tid][sid]=val;
  const p=document.getElementById('abtn_p_'+sid);
  const a=document.getElementById('abtn_a_'+sid);
  if(p&&a){p.style.opacity=val==='present'?'1':'.35';a.style.opacity=val==='absent'?'1':'.35';}
}

function saveAtt(){
  closeM('mAtt');
  showToast('✓ Davamiyyət saxlanıldı','green');
  if(activePanel==='att') renderPanel('att');
}

/* ════════════════════════════════════════
   MODAL — TASK
════════════════════════════════════════ */
function addTask(){
  const lesson=document.getElementById('tLesson').value;
  const topic=document.getElementById('tTopic').value.trim();
  const hw=document.getElementById('tHW').value.trim();
  const note=document.getElementById('tNote').value.trim();
  const date=document.getElementById('tDate').value||new Date().toISOString().slice(0,10);
  if(!topic){showToast('Mövzunu daxil edin','');return;}
  const d=new Date(date);
  const month=d.getMonth();
  const id=taskSeq++;
  tasks.push({id,lesson:parseInt(lesson)||id,topic,hw,note,date,month});
  attendance[id]={};
  if(!grades[month]) grades[month]={};
  grades[month][id]={};
  closeM('mTask');
  showToast('✓ Tapşırıq göndərildi','green');
  ['tLesson','tTopic','tHW','tNote','tDate'].forEach(x=>document.getElementById(x).value='');
  if(activePanel==='tasks') renderPanel('tasks');
  if(activePanel==='dash')  renderPanel('dash');
}

/* ════════════════════════════════════════
   MODAL — NOTICE
════════════════════════════════════════ */
function addNotice(){
  const title=document.getElementById('nTitle').value.trim();
  const body=document.getElementById('nBody').value.trim();
  if(!title||!body){showToast('Başlıq və mətni doldurun','');return;}
  notices.push({id:noticeSeq++,title,body,date:todayStr(),month:NOW_MONTH});
  closeM('mNotice');
  showToast('✓ Elan yayımlandı','green');
  document.getElementById('nTitle').value='';
  document.getElementById('nBody').value='';
  if(activePanel==='notices') renderPanel('notices');
  if(activePanel==='dash') renderPanel('dash');
}

/* ════════════════════════════════════════
   MODAL — ADD STUDENT
════════════════════════════════════════ */
function addStudent(){
  const name=document.getElementById('asName').value.trim();
  const user=document.getElementById('asUser').value.trim();
  const parent=document.getElementById('asParent').value.trim();
  const phone=document.getElementById('asPhone').value.trim();
  if(!name||!user){showToast('Ad və istifadəçi adını daxil edin','');return;}
  const id=STUDENTS.length+1;
  STUDENTS.push({id,name,user,parent:parent||'Valideyn',phone:phone||'+994'});
  closeM('mAddStu');
  showToast('✓ Şagird əlavə edildi','green');
  ['asName','asUser','asParent','asPhone'].forEach(x=>document.getElementById(x).value='');
  if(activePanel==='stus') renderPanel('stus');
}

/* ════════════════════════════════════════
   MODAL — PARENT MSG
════════════════════════════════════════ */
function openParentMsg(sid){
  parentMsgSid=sid;
  const s=STUDENTS.find(x=>x.id===sid);
  document.getElementById('mParentTitle').textContent=`${s.name} — Valideynə Mesaj`;
  document.getElementById('mParentInfo').innerHTML=`👤 <strong>${s.parent}</strong><br>📞 ${s.phone}`;
  document.getElementById('parentMsg').value='';
  openM('mParent');
}

function sendParentMsg(){
  const msg=document.getElementById('parentMsg').value.trim();
  if(!msg){showToast('Mesajı daxil edin','');return;}
  const s=STUDENTS.find(x=>x.id===parentMsgSid);
  closeM('mParent');
  showToast(`✓ ${s.parent}-ə mesaj göndərildi`,'green');
}

/* ════════════════════════════════════════
   MODAL — STUDENT DETAIL
════════════════════════════════════════ */
function openStuDetail(sid){
  const s=STUDENTS.find(x=>x.id===sid);
  document.getElementById('sdName').textContent=s.name;
  const avg=overallAvg(sid);
  const abs=stuAbsent(sid);
  const attPct=stuAttPct(sid);
  const ranked=rankStudents(NOW_MONTH);
  const rank=ranked.findIndex(x=>x.id===sid)+1;

  const recentGrades=tasks.slice(-5).map(t=>{
    const g=grades[t.month]?.[t.id]?.[sid];
    return `<div style="display:flex;justify-content:space-between;padding:8px 0;border-bottom:1px solid var(--border2);font-size:12px">
      <span>D${t.lesson} — ${t.topic.split(' ')[0]}</span>
      <span class="badge ${g!==undefined?scoreColor(g):'o'}">${g!==undefined?g+'/10':'—'}</span>
    </div>`;
  }).join('');

  document.getElementById('sdBody').innerHTML=`
  <div class="ms-grid" style="margin-bottom:14px">
    <div class="ms-card blue"><div class="ms-label">Orta bal</div><div class="ms-val">${avg??'—'}</div></div>
    <div class="ms-card green"><div class="ms-label">Reytinq</div><div class="ms-val">${rank}.</div></div>
    <div class="ms-card red"><div class="ms-label">Qayib</div><div class="ms-val">${abs}</div></div>
    <div class="ms-card purple"><div class="ms-label">İştirak</div><div class="ms-val">${attPct}%</div></div>
  </div>
  <div style="font-size:12px;color:var(--text2);margin-bottom:4px;font-weight:600;text-transform:uppercase;letter-spacing:.06em">Son qiymətlər</div>
  ${recentGrades}
  <div style="font-size:12px;color:var(--text2);margin:12px 0 4px;font-weight:600;text-transform:uppercase;letter-spacing:.06em">Valideyn</div>
  <div class="parent-row" style="margin:0">
    <div><div class="parent-name">${s.parent}</div><div class="parent-num">📞 ${s.phone}</div></div>
    <button class="msg-btn" onclick="closeM('mStuDetail');openParentMsg(${sid})">Mesaj</button>
  </div>`;
  openM('mStuDetail');
}

/* ════════════════════════════════════════
   MONTH END — AUTO WINNER NOTICE
════════════════════════════════════════ */
(function checkMonthWinner(){
  const prevMonth=NOW_MONTH-1;
  const exists=notices.some(n=>n.winner&&n.month===prevMonth);
  if(!exists){
    const ranked=rankStudents(prevMonth);
    const top=ranked.slice(0,3).filter(s=>stuAvg(s.id,prevMonth)!==null);
    if(top.length){
      const body=top.map((s,i)=>`${i+1}. ${s.name} — ${stuAvg(s.id,prevMonth)}/10`).join('\n');
      notices.unshift({
        id:noticeSeq++,
        title:`🏆 ${MONTHS[prevMonth]} Ayının Qalibləri!`,
        body:body.split('\n').join('<br>'),
        date:'1 '+MONTHS[NOW_MONTH].toLowerCase().slice(0,3),
        month:prevMonth,
        winner:true,
      });
    }
  }
})();

/* ════════════════════════════════════════
   UTILS
════════════════════════════════════════ */
function openM(id){document.getElementById(id).classList.add('open')}
function closeM(id){document.getElementById(id).classList.remove('open')}
document.querySelectorAll('.modal-ov').forEach(o=>o.addEventListener('click',e=>{if(e.target===o)o.classList.remove('open')}));

let toastTmr;
function showToast(msg,type){
  const t=document.getElementById('toast');
  t.textContent=msg;t.className='toast'+(type?' '+type:'');
  t.classList.add('show');
  clearTimeout(toastTmr);
  toastTmr=setTimeout(()=>t.classList.remove('show'),2800);
}

// Set today's date in task form
document.getElementById('tDate').value=new Date().toISOString().slice(0,10);
</script>
</body>
</html>
