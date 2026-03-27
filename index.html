<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agenda 2026 — GE Cadetes de Mafeking</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=Source+Sans+3:wght@300;400;600&display=swap" rel="stylesheet">
<style>
  :root {
    --verde: #2d5a27;
    --verde-claro: #4a7c42;
    --creme: #f5f0e8;
    --bege: #e8dfc8;
    --dourado: #c4962a;
    --cinza: #4a4a4a;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { background-color: var(--creme); font-family: 'Source Sans 3', sans-serif; color: var(--cinza); min-height: 100vh; }

  /* HEADER */
  .header { background: var(--verde); color: var(--creme); text-align: center; padding: 48px 24px 36px; position: relative; overflow: hidden; }
  .header::before { content: ''; position: absolute; inset: 0; background: repeating-linear-gradient(45deg, transparent, transparent 20px, rgba(255,255,255,0.025) 20px, rgba(255,255,255,0.025) 40px); }
  .header-badge { display: inline-block; border: 2px solid var(--dourado); color: var(--dourado); font-size: 11px; font-weight: 600; letter-spacing: 3px; text-transform: uppercase; padding: 5px 16px; margin-bottom: 16px; position: relative; }
  .header h1 { font-family: 'Playfair Display', serif; font-size: clamp(28px, 6vw, 52px); font-weight: 900; letter-spacing: -1px; line-height: 1.1; position: relative; margin-bottom: 6px; }
  .header h1 span { color: var(--dourado); }
  .header .subtitle { font-size: 13px; letter-spacing: 2px; text-transform: uppercase; opacity: 0.7; position: relative; margin-top: 10px; }

  /* LEGENDA */
  .legenda-wrap { background: var(--verde-claro); padding: 16px 24px; display: flex; flex-wrap: wrap; gap: 12px 24px; justify-content: center; align-items: center; }
  .legenda-label { font-size: 11px; color: rgba(255,255,255,0.6); letter-spacing: 2px; text-transform: uppercase; margin-right: 4px; }
  .leg-item { display: flex; align-items: center; gap: 7px; font-size: 12px; color: var(--creme); font-weight: 600; letter-spacing: 0.5px; }
  .leg-dot { width: 11px; height: 11px; border-radius: 3px; flex-shrink: 0; }

  /* TOOLBAR */
  .toolbar { max-width: 860px; margin: 28px auto 0; padding: 0 20px; display: flex; justify-content: space-between; align-items: center; gap: 12px; flex-wrap: wrap; }
  .toolbar-right { display: flex; gap: 10px; align-items: center; }

  .btn-add { display: flex; align-items: center; gap: 8px; background: var(--verde); color: white; border: none; border-radius: 8px; padding: 10px 20px; font-family: 'Source Sans 3', sans-serif; font-size: 14px; font-weight: 600; cursor: pointer; letter-spacing: 0.5px; transition: background 0.2s, transform 0.15s; box-shadow: 0 2px 8px rgba(0,0,0,0.15); }
  .btn-add:hover { background: #3d7a35; transform: translateY(-1px); }
  .btn-add:disabled { background: #aaa; cursor: not-allowed; transform: none; box-shadow: none; }

  .btn-lock { display: flex; align-items: center; gap: 7px; background: white; color: var(--cinza); border: 1.5px solid #ddd; border-radius: 8px; padding: 9px 16px; font-family: 'Source Sans 3', sans-serif; font-size: 13px; font-weight: 600; cursor: pointer; transition: all 0.2s; }
  .btn-lock:hover { border-color: var(--verde); color: var(--verde); }
  .btn-lock.unlocked { background: #edf7eb; border-color: var(--verde); color: var(--verde); }

  .status-db { font-size: 12px; color: #999; display: flex; align-items: center; gap: 6px; }
  .status-dot { width: 8px; height: 8px; border-radius: 50%; background: #ccc; transition: background 0.3s; }
  .status-dot.online { background: #4caf50; }
  .status-dot.offline { background: #f44336; }

  /* CONTEÚDO */
  .content { max-width: 860px; margin: 0 auto; padding: 28px 20px 60px; }
  .loading { text-align: center; padding: 60px 20px; color: #999; font-size: 14px; }
  .loading-spinner { width: 32px; height: 32px; border: 3px solid #ddd; border-top-color: var(--verde); border-radius: 50%; animation: spin 0.8s linear infinite; margin: 0 auto 16px; }
  @keyframes spin { to { transform: rotate(360deg); } }

  /* MÊS */
  .mes-bloco { margin-bottom: 36px; opacity: 0; transform: translateY(16px); animation: fadeUp 0.5s ease forwards; }
  @keyframes fadeUp { to { opacity: 1; transform: translateY(0); } }
  .mes-header { display: flex; align-items: center; gap: 14px; margin-bottom: 14px; }
  .mes-nome { font-family: 'Playfair Display', serif; font-size: 22px; font-weight: 700; color: var(--verde); text-transform: uppercase; letter-spacing: 1px; white-space: nowrap; }
  .mes-linha { flex: 1; height: 1px; background: linear-gradient(to right, var(--bege), transparent); }

  /* EVENTO CARD */
  .eventos-lista { display: flex; flex-direction: column; gap: 8px; }
  .evento-card { display: grid; grid-template-columns: 64px 1fr auto; border-radius: 8px; overflow: hidden; box-shadow: 0 1px 4px rgba(0,0,0,0.07); transition: transform 0.15s ease, box-shadow 0.15s ease; }
  .evento-card:hover { transform: translateY(-2px); box-shadow: 0 4px 14px rgba(0,0,0,0.12); }
  .evento-data { display: flex; flex-direction: column; align-items: center; justify-content: center; padding: 12px 6px; color: white; font-weight: 700; line-height: 1.1; }
  .evento-dia { font-size: 22px; font-family: 'Playfair Display', serif; }
  .evento-dia-semana { font-size: 9px; letter-spacing: 1px; text-transform: uppercase; opacity: 0.85; margin-top: 2px; }
  .evento-info { background: white; padding: 12px 16px; display: flex; flex-direction: column; justify-content: center; }
  .evento-titulo { font-size: 14px; font-weight: 600; color: var(--cinza); line-height: 1.3; }
  .evento-descricao { font-size: 12px; color: #888; margin-top: 3px; font-style: italic; }
  .evento-tag { display: inline-block; font-size: 10px; font-weight: 600; letter-spacing: 1px; text-transform: uppercase; padding: 2px 8px; border-radius: 20px; margin-top: 5px; width: fit-content; color: white; }

  /* AÇÕES */
  .evento-acoes { background: white; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 4px; padding: 8px 10px; border-left: 1px solid #f0f0f0; min-width: 44px; }
  .btn-icon { background: none; border: none; cursor: pointer; border-radius: 6px; padding: 5px; display: flex; align-items: center; justify-content: center; transition: background 0.15s; color: #aaa; }
  .btn-icon:hover { background: #f5f5f5; color: #555; }
  .btn-icon.delete:hover { background: #fff0f0; color: #c0392b; }
  .btn-icon:disabled { opacity: 0.25; cursor: not-allowed; }
  .btn-icon:disabled:hover { background: none; color: #aaa; }

  /* MODAL */
  .modal-overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.55); z-index: 1000; align-items: center; justify-content: center; padding: 20px; backdrop-filter: blur(2px); }
  .modal-overlay.active { display: flex; }
  .modal { background: white; border-radius: 14px; width: 100%; max-width: 480px; box-shadow: 0 20px 60px rgba(0,0,0,0.25); overflow: hidden; animation: modalIn 0.2s ease; }
  @keyframes modalIn { from { opacity:0; transform: scale(0.95) translateY(10px); } to { opacity:1; transform: none; } }
  .modal-header { background: var(--verde); color: white; padding: 20px 24px; display: flex; align-items: center; justify-content: space-between; }
  .modal-header h2 { font-family: 'Playfair Display', serif; font-size: 18px; font-weight: 700; }
  .modal-close { background: none; border: none; color: rgba(255,255,255,0.7); cursor: pointer; font-size: 22px; line-height: 1; padding: 2px 6px; border-radius: 4px; transition: color 0.15s, background 0.15s; }
  .modal-close:hover { color: white; background: rgba(255,255,255,0.15); }
  .modal-body { padding: 24px; display: flex; flex-direction: column; gap: 16px; }
  .field { display: flex; flex-direction: column; gap: 6px; }
  .field label { font-size: 12px; font-weight: 600; letter-spacing: 1px; text-transform: uppercase; color: #888; }
  .field input, .field select, .field textarea { border: 1.5px solid #e0e0e0; border-radius: 8px; padding: 10px 12px; font-family: 'Source Sans 3', sans-serif; font-size: 14px; color: var(--cinza); transition: border-color 0.15s; outline: none; background: #fafafa; }
  .field input:focus, .field select:focus, .field textarea:focus { border-color: var(--verde); background: white; }
  .field textarea { resize: vertical; min-height: 64px; }
  .field-row { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
  .cat-select-wrap { position: relative; }
  .cat-preview { position: absolute; right: 12px; top: 50%; transform: translateY(-50%); width: 14px; height: 14px; border-radius: 4px; pointer-events: none; border: 1px solid rgba(0,0,0,0.1); }
  .cat-select-wrap select { padding-right: 36px; }
  .modal-footer { padding: 16px 24px 24px; display: flex; gap: 10px; justify-content: flex-end; }
  .btn-cancel { background: #f0f0f0; border: none; border-radius: 8px; padding: 10px 20px; font-family: 'Source Sans 3', sans-serif; font-size: 14px; font-weight: 600; cursor: pointer; color: #666; transition: background 0.15s; }
  .btn-cancel:hover { background: #e0e0e0; }
  .btn-save { background: var(--verde); border: none; border-radius: 8px; padding: 10px 24px; font-family: 'Source Sans 3', sans-serif; font-size: 14px; font-weight: 600; cursor: pointer; color: white; transition: background 0.15s; }
  .btn-save:hover { background: #3d7a35; }

  /* MODAL SENHA */
  .senha-modal { background: white; border-radius: 14px; width: 100%; max-width: 360px; box-shadow: 0 20px 60px rgba(0,0,0,0.25); overflow: hidden; animation: modalIn 0.2s ease; }
  .senha-body { padding: 28px; text-align: center; }
  .senha-icon { font-size: 36px; margin-bottom: 12px; }
  .senha-body h3 { font-family: 'Playfair Display', serif; font-size: 20px; color: var(--verde); margin-bottom: 8px; }
  .senha-body p { font-size: 13px; color: #888; margin-bottom: 20px; }
  .senha-input-wrap { position: relative; margin-bottom: 8px; }
  .senha-input-wrap input { width: 100%; border: 1.5px solid #e0e0e0; border-radius: 8px; padding: 11px 16px; font-size: 15px; font-family: 'Source Sans 3', sans-serif; outline: none; text-align: center; letter-spacing: 2px; }
  .senha-input-wrap input:focus { border-color: var(--verde); }
  .senha-erro { font-size: 12px; color: #c0392b; min-height: 18px; margin-bottom: 12px; }
  .btn-entrar { width: 100%; background: var(--verde); color: white; border: none; border-radius: 8px; padding: 12px; font-family: 'Source Sans 3', sans-serif; font-size: 14px; font-weight: 600; cursor: pointer; transition: background 0.2s; }
  .btn-entrar:hover { background: #3d7a35; }

  /* CONFIRM */
  .confirm-overlay { display: none; position: fixed; inset: 0; background: rgba(0,0,0,0.5); z-index: 1100; align-items: center; justify-content: center; padding: 20px; }
  .confirm-overlay.active { display: flex; }
  .confirm-box { background: white; border-radius: 12px; padding: 28px; max-width: 360px; width: 100%; box-shadow: 0 10px 40px rgba(0,0,0,0.2); text-align: center; }
  .confirm-box h3 { font-family: 'Playfair Display', serif; font-size: 18px; color: #c0392b; margin-bottom: 10px; }
  .confirm-box p { font-size: 14px; color: #666; margin-bottom: 20px; line-height: 1.5; }
  .confirm-actions { display: flex; gap: 10px; justify-content: center; }
  .btn-del { background: #c0392b; color: white; border: none; border-radius: 8px; padding: 10px 22px; font-size: 14px; font-weight: 600; cursor: pointer; font-family: 'Source Sans 3', sans-serif; transition: background 0.15s; }
  .btn-del:hover { background: #a93226; }

  footer { text-align: center; padding: 24px; background: var(--verde); color: rgba(255,255,255,0.5); font-size: 12px; letter-spacing: 1px; }
  footer strong { color: var(--dourado); }

  @media (max-width: 500px) {
    .evento-card { grid-template-columns: 52px 1fr auto; }
    .evento-dia { font-size: 18px; }
    .mes-nome { font-size: 18px; }
    .field-row { grid-template-columns: 1fr; }
    .toolbar { flex-direction: column; align-items: flex-start; }
  }
</style>
</head>
<body>

<div class="header">
  <div class="header-badge">Calendário Oficial</div>
  <h1>GE Cadetes de <span>Mafeking</span></h1>
  <div class="subtitle">Programação 2026</div>
</div>

<div class="legenda-wrap">
  <span class="legenda-label">Legenda</span>
  <div class="leg-item"><div class="leg-dot" style="background:#7b2fa0"></div>Grupo</div>
  <div class="leg-item"><div class="leg-dot" style="background:#f5c800"></div>Alcateia</div>
  <div class="leg-item"><div class="leg-dot" style="background:#2d7a2d"></div>Escoteira</div>
  <div class="leg-item"><div class="leg-dot" style="background:#6e1020"></div>Sênior</div>
  <div class="leg-item"><div class="leg-dot" style="background:#e01010"></div>Clã</div>
  <div class="leg-item"><div class="leg-dot" style="background:#2d5a27"></div>Acampamento</div>
  <div class="leg-item"><div class="leg-dot" style="background:#999"></div>Sem atividade</div>
</div>

<div class="toolbar">
  <div class="status-db">
    <div class="status-dot" id="statusDot"></div>
    <span id="statusTxt">Conectando…</span>
  </div>
  <div class="toolbar-right">
    <button class="btn-lock" id="btnLock" onclick="toggleSenha()">
      🔒 Modo edição
    </button>
    <button class="btn-add" id="btnAdd" onclick="abrirModal()" disabled>
      <svg width="16" height="16" viewBox="0 0 16 16" fill="none"><path d="M8 2v12M2 8h12" stroke="white" stroke-width="2.2" stroke-linecap="round"/></svg>
      Adicionar evento
    </button>
  </div>
</div>

<div class="content" id="agenda">
  <div class="loading">
    <div class="loading-spinner"></div>
    Carregando agenda…
  </div>
</div>

<footer><strong>GE Cadetes de Mafeking</strong> &nbsp;·&nbsp; Calendário 2026</footer>

<!-- MODAL EVENTO -->
<div class="modal-overlay" id="modalOverlay">
  <div class="modal">
    <div class="modal-header">
      <h2 id="modalTitulo">Novo Evento</h2>
      <button class="modal-close" onclick="fecharModal()">×</button>
    </div>
    <div class="modal-body">
      <div class="field-row">
        <div class="field">
          <label>Data de início</label>
          <input type="date" id="fData">
        </div>
        <div class="field">
          <label>Data de fim (opcional)</label>
          <input type="date" id="fDataFim">
        </div>
      </div>
      <div class="field">
        <label>Título do evento</label>
        <input type="text" id="fTitulo" placeholder="Ex: Acampamento Escoteira">
      </div>
      <div class="field">
        <label>Seção / Categoria</label>
        <div class="cat-select-wrap">
          <select id="fCategoria" onchange="atualizarPreview()">
            <option value="especial">Grupo / Especial</option>
            <option value="alcateia">Alcateia</option>
            <option value="escoteira">Escoteira</option>
            <option value="senior">Sênior</option>
            <option value="cla">Clã</option>
            <option value="acampamento">Acampamento</option>
            <option value="sem">Sem atividade</option>
          </select>
          <div class="cat-preview" id="catPreview"></div>
        </div>
      </div>
      <div class="field">
        <label>Observação (opcional)</label>
        <textarea id="fDescricao" placeholder="Ex: Atividade com outro grupo, horário especial…"></textarea>
      </div>
    </div>
    <div class="modal-footer">
      <button class="btn-cancel" onclick="fecharModal()">Cancelar</button>
      <button class="btn-save" onclick="salvarEvento()">Salvar</button>
    </div>
  </div>
</div>

<!-- MODAL SENHA -->
<div class="modal-overlay" id="senhaOverlay">
  <div class="senha-modal">
    <div class="senha-body">
      <div class="senha-icon">🔐</div>
      <h3>Modo edição</h3>
      <p>Digite a senha para poder adicionar e editar eventos.</p>
      <div class="senha-input-wrap">
        <input type="password" id="senhaInput" placeholder="••••••••" onkeydown="if(event.key==='Enter') verificarSenha()">
      </div>
      <div class="senha-erro" id="senhaErro"></div>
      <button class="btn-entrar" onclick="verificarSenha()">Entrar</button>
    </div>
  </div>
</div>

<!-- CONFIRM DELETE -->
<div class="confirm-overlay" id="confirmOverlay">
  <div class="confirm-box">
    <h3>Excluir evento?</h3>
    <p id="confirmMsg">Esta ação não pode ser desfeita.</p>
    <div class="confirm-actions">
      <button class="btn-cancel" onclick="fecharConfirm()">Cancelar</button>
      <button class="btn-del" onclick="confirmarExclusao()">Excluir</button>
    </div>
  </div>
</div>

<!-- Firebase -->
<script type="module">
import { initializeApp } from "https://www.gstatic.com/firebasejs/10.12.0/firebase-app.js";
import { getDatabase, ref, onValue, set, remove, push } from "https://www.gstatic.com/firebasejs/10.12.0/firebase-database.js";

const firebaseConfig = {
  apiKey: "AIzaSyBOtFGD8DjOhb-SJXokHDxS4caXtVhUco0",
  authDomain: "agenda-ge-cadetes-mafeking.firebaseapp.com",
  databaseURL: "https://agenda-ge-cadetes-mafeking-default-rtdb.firebaseio.com",
  projectId: "agenda-ge-cadetes-mafeking",
  storageBucket: "agenda-ge-cadetes-mafeking.firebasestorage.app",
  messagingSenderId: "173849084331",
  appId: "1:173849084331:web:634fd5b3c10563db6d92ee",
};

const app = initializeApp(firebaseConfig);
const db  = getDatabase(app);

// ── Constantes ────────────────────────────────────────────
const SENHA = "cadetes10";
const DIAS  = ['Dom','Seg','Ter','Qua','Qui','Sex','Sáb'];
const MESES = ['Janeiro','Fevereiro','Março','Abril','Maio','Junho','Julho','Agosto','Setembro','Outubro','Novembro','Dezembro'];
const CORES = { especial:'#7b2fa0', acampamento:'#2d5a27', alcateia:'#f5c800', senior:'#6e1020', cla:'#e01010', sem:'#999', grupo:'#7b2fa0', escoteira:'#2d7a2d' };
const TAGS  = { especial:'Grupo', alcateia:'Alcateia', escoteira:'Escoteira', senior:'Sênior', cla:'Clã', acampamento:'Acampamento', sem:'Sem atividade', grupo:'Grupo' };

const EVENTOS_BASE = [
  {id:'b1', data:'2026-03-14', titulo:'Início das atividades', categoria:'especial'},
  {id:'b2', data:'2026-03-28', titulo:'Assembleia de pais', categoria:'especial', descricao:'⏰ 17h30–18h30'},
  {id:'b3', data:'2026-04-04', titulo:'Sem atividade', categoria:'sem'},
  {id:'b4', data:'2026-04-11', titulo:'Promessa Fabi – manhã', categoria:'escoteira'},
  {id:'b5', data:'2026-04-25', titulo:'Acampamento Escoteira', categoria:'acampamento', descricao:'📅 25–26/abr'},
  {id:'b6', data:'2026-04-25', titulo:'Acampamento Sênior', categoria:'senior', descricao:'📅 25–26/abr'},
  {id:'b7', data:'2026-05-09', titulo:'Atividade externa Alcateia', categoria:'alcateia', descricao:'Atividade com outro grupo'},
  {id:'b8', data:'2026-05-16', titulo:'Dia da família', categoria:'especial'},
  {id:'b9', data:'2026-06-07', titulo:'Muteco – Escoteira', categoria:'escoteira'},
  {id:'b10',data:'2026-06-13', titulo:'Saída cultural Alcateia', categoria:'alcateia'},
  {id:'b11',data:'2026-06-21', titulo:'Virando a noite', categoria:'especial', descricao:'Possivelmente com Japão'},
  {id:'b12',data:'2026-06-27', titulo:'Vigília Clã', categoria:'cla'},
  {id:'b13',data:'2026-07-11', titulo:'Sem atividade – Festa Julina', categoria:'sem'},
  {id:'b14',data:'2026-07-12', titulo:'Festa Julina', categoria:'especial'},
  {id:'b15',data:'2026-07-25', titulo:'Jogos noturnos – Sênior', categoria:'senior', descricao:'📅 25–26/jul'},
  {id:'b16',data:'2026-08-15', titulo:'Atividade externa – Sênior', categoria:'senior'},
  {id:'b17',data:'2026-08-22', titulo:'Aniversário do grupo', categoria:'especial'},
  {id:'b18',data:'2026-09-01', titulo:'Atividade externa – Sênior', categoria:'senior'},
  {id:'b19',data:'2026-09-07', titulo:'Desfile', categoria:'especial'},
  {id:'b20',data:'2026-09-19', titulo:'Atividade externa – Sênior', categoria:'senior'},
  {id:'b21',data:'2026-10-03', titulo:'Bivaque – Escoteira', categoria:'acampamento'},
  {id:'b22',data:'2026-10-03', titulo:'Atividade externa Alcateia – acantonamento', categoria:'alcateia', descricao:'Acantonamento'},
  {id:'b23',data:'2026-10-10', titulo:'Sem atividade', categoria:'sem'},
  {id:'b24',data:'2026-10-10', titulo:'Ação comunitária ou mutirão – Clã', categoria:'cla', descricao:'📅 10–12/out'},
  {id:'b25',data:'2026-10-31', titulo:'Saída externa – Sênior', categoria:'senior'},
  {id:'b26',data:'2026-12-05', titulo:'Acampamento de grupo', categoria:'acampamento', descricao:'📅 5–6/dez'},
];

// ── Estado ────────────────────────────────────────────────
let modoEdicao = false;
let editId = null;
let delId  = null;
let dbData = { editados: {}, adicionados: {} }; // dados do Firebase

// ── Firebase sync ─────────────────────────────────────────
const dbRef = ref(db, 'agenda');
onValue(dbRef, (snapshot) => {
  dbData = snapshot.val() || { editados: {}, adicionados: {} };
  if (!dbData.editados)   dbData.editados   = {};
  if (!dbData.adicionados) dbData.adicionados = {};
  setStatus(true);
  render();
}, (err) => {
  setStatus(false);
  console.error(err);
});

function setStatus(online) {
  document.getElementById('statusDot').className = 'status-dot ' + (online ? 'online' : 'offline');
  document.getElementById('statusTxt').textContent = online ? 'Sincronizado' : 'Sem conexão';
}

function getEventos() {
  const base = EVENTOS_BASE
    .filter(e => dbData.editados[e.id] !== null && dbData.editados[e.id] !== 'DELETED')
    .map(e => dbData.editados[e.id] ? { ...e, ...dbData.editados[e.id] } : e);
  const extras = Object.values(dbData.adicionados || {});
  return [...base, ...extras];
}

// ── Salvar no Firebase ────────────────────────────────────
async function salvarNoFirebase(path, value) {
  await set(ref(db, path), value);
}
async function removerNoFirebase(path) {
  await remove(ref(db, path));
}

// ── Render ────────────────────────────────────────────────
function parseDate(s) { const [y,m,d] = s.split('-').map(Number); return new Date(y, m-1, d); }

function render() {
  const agenda = document.getElementById('agenda');
  agenda.innerHTML = '';
  const todos = getEventos().filter(e => e.data);
  if (!todos.length) { agenda.innerHTML = '<div class="loading">Nenhum evento encontrado.</div>'; return; }

  const porMes = {};
  for (const ev of todos) {
    const d = parseDate(ev.data);
    const k = d.getMonth();
    if (!porMes[k]) porMes[k] = [];
    porMes[k].push({ ...ev, _d: d });
  }

  Object.keys(porMes).sort((a,b) => a-b).forEach((mi, i) => {
    const evs = porMes[mi].sort((a,b) => a._d - b._d);
    const bloco = document.createElement('div');
    bloco.className = 'mes-bloco';
    bloco.style.animationDelay = `${i*60}ms`;
    bloco.innerHTML = `<div class="mes-header"><div class="mes-nome">${MESES[mi]}</div><div class="mes-linha"></div></div><div class="eventos-lista" id="ml-${mi}"></div>`;
    agenda.appendChild(bloco);
    const lista = bloco.querySelector(`#ml-${mi}`);
    evs.forEach(ev => lista.appendChild(makeCard(ev)));
  });
}

function makeCard(ev) {
  const dia = ev._d.getDate();
  const ds  = DIAS[ev._d.getDay()];
  const cor = CORES[ev.categoria] || '#888';
  const tag = TAGS[ev.categoria]  || ev.categoria;
  const darkTag = ev.categoria === 'alcateia';

  let duracaoHtml = '';
  if (ev.dataFim && ev.dataFim !== ev.data) {
    const fim = parseDate(ev.dataFim);
    const mf  = fim.getMonth()+1;
    duracaoHtml = `<div class="evento-descricao">📅 ${dia}–${fim.getDate()}/${mf<10?'0'+mf:mf}</div>`;
  }

  const card = document.createElement('div');
  card.className = 'evento-card';
  const dis = modoEdicao ? '' : 'disabled';
  card.innerHTML = `
    <div class="evento-data" style="background:${cor}">
      <div class="evento-dia">${String(dia).padStart(2,'0')}</div>
      <div class="evento-dia-semana">${ds}</div>
    </div>
    <div class="evento-info">
      <div class="evento-titulo">${ev.titulo}</div>
      ${ev.descricao ? `<div class="evento-descricao">${ev.descricao}</div>` : ''}
      ${duracaoHtml}
      <div class="evento-tag" style="background:${cor};${darkTag?'color:#333':''}">${tag}</div>
    </div>
    <div class="evento-acoes">
      <button class="btn-icon" title="Editar" ${dis} onclick="abrirEditar('${ev.id}')">
        <svg width="15" height="15" viewBox="0 0 20 20" fill="none"><path d="M13.5 3.5L16.5 6.5L7 16H4v-3L13.5 3.5z" stroke="currentColor" stroke-width="1.8" stroke-linejoin="round"/><path d="M11.5 5.5l3 3" stroke="currentColor" stroke-width="1.8"/></svg>
      </button>
      <button class="btn-icon delete" title="Excluir" ${dis} onclick="pedirExclusao('${ev.id}', \`${ev.titulo.replace(/`/g,"'")}\`)">
        <svg width="15" height="15" viewBox="0 0 20 20" fill="none"><path d="M4 6h12M8 6V4h4v2M7 6l1 10h4l1-10" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </button>
    </div>`;
  return card;
}

// ── Senha ─────────────────────────────────────────────────
window.toggleSenha = function() {
  if (modoEdicao) {
    // Sair do modo edição
    modoEdicao = false;
    document.getElementById('btnLock').textContent = '🔒 Modo edição';
    document.getElementById('btnLock').classList.remove('unlocked');
    document.getElementById('btnAdd').disabled = true;
    render();
  } else {
    document.getElementById('senhaInput').value = '';
    document.getElementById('senhaErro').textContent = '';
    document.getElementById('senhaOverlay').classList.add('active');
    setTimeout(() => document.getElementById('senhaInput').focus(), 100);
  }
};

window.verificarSenha = function() {
  const val = document.getElementById('senhaInput').value;
  if (val === SENHA) {
    modoEdicao = true;
    document.getElementById('senhaOverlay').classList.remove('active');
    document.getElementById('btnLock').innerHTML = '🔓 Edição ativa';
    document.getElementById('btnLock').classList.add('unlocked');
    document.getElementById('btnAdd').disabled = false;
    render();
  } else {
    document.getElementById('senhaErro').textContent = 'Senha incorreta. Tente novamente.';
    document.getElementById('senhaInput').select();
  }
};

// ── Modal evento ──────────────────────────────────────────
window.abrirModal = function() {
  editId = null;
  document.getElementById('modalTitulo').textContent = 'Novo Evento';
  document.getElementById('fData').value = '';
  document.getElementById('fDataFim').value = '';
  document.getElementById('fTitulo').value = '';
  document.getElementById('fCategoria').value = 'especial';
  document.getElementById('fDescricao').value = '';
  atualizarPreview();
  document.getElementById('modalOverlay').classList.add('active');
  setTimeout(() => document.getElementById('fTitulo').focus(), 100);
};

window.abrirEditar = function(id) {
  if (!modoEdicao) return;
  editId = id;
  const ev = getEventos().find(e => e.id === id);
  if (!ev) return;
  document.getElementById('modalTitulo').textContent = 'Editar Evento';
  document.getElementById('fData').value = ev.data;
  document.getElementById('fDataFim').value = ev.dataFim || '';
  document.getElementById('fTitulo').value = ev.titulo;
  document.getElementById('fCategoria').value = ev.categoria;
  document.getElementById('fDescricao').value = ev.descricao || '';
  atualizarPreview();
  document.getElementById('modalOverlay').classList.add('active');
};

window.fecharModal = function() { document.getElementById('modalOverlay').classList.remove('active'); editId = null; };

window.atualizarPreview = function() {
  const cat = document.getElementById('fCategoria').value;
  document.getElementById('catPreview').style.background = CORES[cat] || '#888';
};

window.salvarEvento = async function() {
  const data  = document.getElementById('fData').value;
  const titulo = document.getElementById('fTitulo').value.trim();
  if (!data || !titulo) { alert('Preencha a data e o título.'); return; }

  const ev = {
    data,
    dataFim:   document.getElementById('fDataFim').value || '',
    titulo,
    categoria: document.getElementById('fCategoria').value,
    descricao: document.getElementById('fDescricao').value.trim(),
  };

  const btnSave = document.querySelector('.btn-save');
  btnSave.textContent = 'Salvando…';
  btnSave.disabled = true;

  try {
    if (editId) {
      ev.id = editId;
      const isBase = EVENTOS_BASE.some(b => b.id === editId);
      if (isBase) {
        await salvarNoFirebase(`agenda/editados/${editId}`, ev);
      } else {
        await salvarNoFirebase(`agenda/adicionados/${editId}`, ev);
      }
    } else {
      const newRef = push(ref(db, 'agenda/adicionados'));
      ev.id = newRef.key;
      await set(newRef, ev);
    }
    fecharModal();
  } catch(e) {
    alert('Erro ao salvar. Verifique sua conexão.');
    console.error(e);
  } finally {
    btnSave.textContent = 'Salvar';
    btnSave.disabled = false;
  }
};

// ── Exclusão ──────────────────────────────────────────────
window.pedirExclusao = function(id, titulo) {
  if (!modoEdicao) return;
  delId = id;
  document.getElementById('confirmMsg').textContent = `Deseja excluir "${titulo}"?`;
  document.getElementById('confirmOverlay').classList.add('active');
};

window.fecharConfirm = function() { document.getElementById('confirmOverlay').classList.remove('active'); delId = null; };

window.confirmarExclusao = async function() {
  if (!delId) return;
  const isBase = EVENTOS_BASE.some(b => b.id === delId);
  try {
    if (isBase) {
      await salvarNoFirebase(`agenda/editados/${delId}`, 'DELETED');
    } else {
      await removerNoFirebase(`agenda/adicionados/${delId}`);
    }
    fecharConfirm();
  } catch(e) {
    alert('Erro ao excluir. Verifique sua conexão.');
    console.error(e);
  }
};

// ── Fechar ao clicar fora ─────────────────────────────────
document.getElementById('modalOverlay').addEventListener('click', e => { if (e.target === e.currentTarget) fecharModal(); });
document.getElementById('confirmOverlay').addEventListener('click', e => { if (e.target === e.currentTarget) fecharConfirm(); });
document.getElementById('senhaOverlay').addEventListener('click', e => { if (e.target === e.currentTarget) document.getElementById('senhaOverlay').classList.remove('active'); });

// Init preview
atualizarPreview();
</script>
</body>
</html>
