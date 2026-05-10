<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Print3D Manager</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@300;400;500;600&family=DM+Mono:wght@400;500&display=swap" rel="stylesheet">
<script src="https://accounts.google.com/gsi/client" async defer></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<style>
:root{--bg:#F7F6F3;--sur:#FFF;--sur2:#F0EEE9;--bdr:#E4E1D9;--bdr2:#CCC9BF;--tx:#1A1916;--mt:#6E6B62;--ac:#2D6AFF;--acb:#EEF3FF;--ok:#1A7F4B;--okb:#EDFAF3;--wn:#B45309;--wnb:#FFF8EC;--dg:#C62828;--dgb:#FFF0F0;--r:10px;--rs:6px}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
body{font-family:'DM Sans',sans-serif;background:var(--bg);color:var(--tx);min-height:100vh;font-size:14px}
#shell{display:flex;min-height:100vh}
#sb{width:228px;background:var(--sur);border-right:1px solid var(--bdr);display:flex;flex-direction:column;flex-shrink:0}
#main{flex:1;display:flex;flex-direction:column;min-width:0}
#topbar{background:var(--sur);border-bottom:1px solid var(--bdr);padding:11px 22px;display:flex;align-items:center;gap:10px;min-height:50px}
#content{flex:1;padding:22px;overflow-y:auto}
.logo{padding:18px 16px 10px}.logo-m{font-family:'DM Mono',monospace;font-size:15px;font-weight:500;color:var(--ac);letter-spacing:.5px}.logo-s{font-size:11px;color:var(--mt);margin-top:2px}
.ns{padding:7px 8px 3px;font-size:10px;font-weight:600;text-transform:uppercase;letter-spacing:1px;color:var(--mt)}
.ni{display:flex;align-items:center;gap:9px;padding:8px 12px;border-radius:var(--rs);margin:1px 8px;cursor:pointer;font-size:13px;color:var(--mt);transition:all .14s}
.ni:hover{background:var(--sur2);color:var(--tx)}.ni.active{background:var(--acb);color:var(--ac);font-weight:500}
.ni-ic{font-size:15px;width:19px;text-align:center}
.sb-bot{margin-top:auto;padding:11px 8px;border-top:1px solid var(--bdr)}
.dr-st{display:flex;align-items:center;gap:8px;padding:8px 12px;border-radius:var(--rs);background:var(--sur2);font-size:12px;cursor:pointer}
.dr-st:hover{background:var(--bdr)}.dr-dot{width:7px;height:7px;border-radius:50%;background:#ccc;flex-shrink:0;transition:background .3s}
.dr-dot.ok{background:var(--ok)}
.ptitle{font-size:15px;font-weight:600;flex:1}
.btn{display:inline-flex;align-items:center;gap:5px;padding:7px 13px;border-radius:var(--rs);border:1px solid var(--bdr2);background:var(--sur);color:var(--tx);font-size:13px;font-family:inherit;cursor:pointer;transition:all .14s;font-weight:500;white-space:nowrap}
.btn:hover{background:var(--sur2)}.btn.pr{background:var(--ac);color:#fff;border-color:var(--ac)}.btn.pr:hover{background:#1a58f0}
.btn.ok{background:var(--ok);color:#fff;border-color:var(--ok)}.btn.wn{color:var(--wn);border-color:#f0d080}.btn.wn:hover{background:var(--wnb)}
.btn.dg{color:var(--dg);border-color:#f8c9c9}.btn.dg:hover{background:var(--dgb)}.btn.sm{padding:4px 9px;font-size:12px}
.sc{display:grid;grid-template-columns:repeat(4,1fr);gap:13px;margin-bottom:22px}
.scard{background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:15px}
.sl{font-size:11px;color:var(--mt);text-transform:uppercase;letter-spacing:.5px;margin-bottom:5px}
.sv{font-size:21px;font-weight:600;font-family:'DM Mono',monospace}.ss{font-size:11px;color:var(--mt);margin-top:3px}
.tw{background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);overflow:hidden}
.th2{display:flex;align-items:center;padding:13px 17px;border-bottom:1px solid var(--bdr);gap:9px;flex-wrap:wrap}
.th2 .ttl{font-size:14px;font-weight:600;flex:1}
.srch{padding:6px 11px;border:1px solid var(--bdr);border-radius:var(--rs);font-size:13px;font-family:inherit;background:var(--bg);width:190px;outline:none}
.srch:focus{border-color:var(--ac)}
table{width:100%;border-collapse:collapse}
th{text-align:left;font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.5px;color:var(--mt);padding:9px 16px;border-bottom:1px solid var(--bdr);background:var(--bg)}
td{padding:10px 16px;border-bottom:1px solid var(--bdr);font-size:13px;vertical-align:middle}
tr:last-child td{border-bottom:none}tr:hover td{background:var(--sur2)}
.badge{display:inline-block;padding:2px 8px;border-radius:20px;font-size:11px;font-weight:500}
.badge.bl{background:var(--acb);color:var(--ac)}.badge.gn{background:var(--okb);color:var(--ok)}
.badge.wn{background:var(--wnb);color:var(--wn)}.badge.gy{background:var(--sur2);color:var(--mt)}.badge.rd{background:var(--dgb);color:var(--dg)}
.mbg{display:none;position:fixed;inset:0;background:rgba(0,0,0,.42);z-index:1000;align-items:center;justify-content:center}
.mbg.open{display:flex}
.modal{background:var(--sur);border-radius:13px;width:580px;max-width:96vw;max-height:92vh;display:flex;flex-direction:column;box-shadow:0 20px 60px rgba(0,0,0,.18)}
.mh{padding:18px 22px 14px;border-bottom:1px solid var(--bdr);display:flex;align-items:center}
.mh h2{font-size:15px;font-weight:600;flex:1}
.mb{padding:18px 22px;overflow-y:auto;flex:1}.mf{padding:14px 22px;border-top:1px solid var(--bdr);display:flex;justify-content:flex-end;gap:8px;flex-wrap:wrap}
.fg{display:flex;flex-direction:column;gap:4px}
.fg label{font-size:12px;font-weight:500;color:var(--mt)}
.fg input,.fg select,.fg textarea{padding:7px 11px;border:1px solid var(--bdr);border-radius:var(--rs);font-size:13px;font-family:inherit;background:var(--sur);color:var(--tx);outline:none}
.fg input:focus,.fg select:focus,.fg textarea:focus{border-color:var(--ac)}
.fg textarea{resize:vertical;min-height:60px}.fg.s2{grid-column:span 2}
.g2{display:grid;grid-template-columns:1fr 1fr;gap:13px}
.g3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:11px}
.sdiv{font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.5px;color:var(--mt);margin:14px 0 9px;border-bottom:1px solid var(--bdr);padding-bottom:5px}
.csec{background:var(--sur2);border-radius:var(--rs);padding:13px;margin-top:4px}
.crow{display:flex;justify-content:space-between;align-items:center;padding:3px 0;font-size:13px}
.crow.tot{border-top:1px solid var(--bdr2);margin-top:5px;padding-top:7px;font-weight:600;font-size:15px;color:var(--ac);font-family:'DM Mono',monospace}
.crow span:last-child{font-family:'DM Mono',monospace}
.empty{text-align:center;padding:55px 20px;color:var(--mt)}.empty .ei{font-size:44px;margin-bottom:11px;opacity:.3}.empty p{font-size:14px;margin-bottom:14px}
.av{border-radius:50%;background:var(--acb);color:var(--ac);display:flex;align-items:center;justify-content:center;font-weight:600;flex-shrink:0}
.qcard{background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:14px;margin-bottom:9px;display:flex;align-items:center;gap:12px;flex-wrap:wrap}
.qcard:hover{border-color:var(--ac)}
#toast{position:fixed;bottom:22px;right:22px;background:var(--tx);color:#fff;padding:9px 16px;border-radius:var(--rs);font-size:13px;transform:translateY(60px);opacity:0;transition:all .3s;z-index:9999;pointer-events:none;max-width:300px}
#toast.show{transform:translateY(0);opacity:1}
.banner{background:var(--wnb);border:1px solid #f0d080;border-radius:var(--r);padding:11px 15px;margin-bottom:18px;display:flex;align-items:center;gap:11px;font-size:13px}
.saving{font-size:12px;color:var(--mt);display:flex;align-items:center;gap:5px}
.cs{background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);margin-bottom:13px;overflow:hidden}
.ch{padding:14px 18px;border-bottom:1px solid var(--bdr);display:flex;align-items:center;justify-content:space-between;gap:11px}
.ch-t h3{font-size:14px;font-weight:600}.ch-t p{font-size:12px;color:var(--mt);margin-top:2px}
.cb{padding:18px}.lr{display:flex;align-items:center;gap:9px;padding:10px 0;border-bottom:1px solid var(--bdr)}
.lr:last-child{border-bottom:none}
.fc{background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:14px;margin-bottom:9px}
.fc.dg{border-color:#f8c9c9;background:var(--dgb)}.fc.wn{border-color:#f0d080;background:var(--wnb)}
.pb{height:5px;background:var(--sur2);border-radius:3px;overflow:hidden;margin-top:7px}
.pf{height:100%;border-radius:3px;transition:width .4s}
.chk-row{display:flex;align-items:center;gap:8px;padding:5px 0;font-size:13px;cursor:pointer}
.chk-row input{width:15px;height:15px;accent-color:var(--ac)}
.tag-chip{display:inline-flex;align-items:center;gap:5px;background:var(--sur2);border:1px solid var(--bdr);border-radius:20px;padding:3px 10px;font-size:12px;margin:3px}
</style>
</head>
<body>
<div id="shell">
<div id="sb">
  <div class="logo"><div class="logo-m">Print3D</div><div class="logo-s">Gestão de impressões</div></div>
  <div style="padding:4px 0">
    <div class="ns">Menu</div>
    <div class="ni active" onclick="nav('dash')"><span class="ni-ic">◈</span>Dashboard</div>
    <div class="ni" onclick="nav('cli')"><span class="ni-ic">◉</span>Clientes</div>
    <div class="ni" onclick="nav('orc')"><span class="ni-ic">◎</span>Orçamentos</div>
    <div class="ni" onclick="nav('fia')"><span class="ni-ic">⊘</span>Fiado / Crédito</div>
    <div class="ni" onclick="nav('calc')"><span class="ni-ic">⊡</span>Calculadora</div>
    <div class="ni" onclick="nav('cfg')"><span class="ni-ic">⚙</span>Configurações</div>
  </div>
  <div class="sb-bot">
    <div class="dr-st" onclick="connectDrive()">
      <div class="dr-dot" id="ddot"></div><span id="dtext" style="color:var(--mt)">Conectar Drive</span>
    </div>
  </div>
</div>
<div id="main">
  <div id="topbar">
    <span class="ptitle" id="ptitle">Dashboard</span>
    <span class="saving" id="saving" style="display:none">↻ Salvando...</span>
    <div id="tact" style="display:flex;gap:7px;flex-wrap:wrap"></div>
  </div>
  <div id="content"></div>
</div>
</div>

<!-- ══ MODAL CLIENTE ══ -->
<div class="mbg" id="m-cli">
<div class="modal" style="width:640px">
  <div class="mh"><h2 id="mc-t">Novo cliente</h2><button class="btn sm" onclick="closeM('m-cli')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div class="sdiv">Dados pessoais</div>
    <div class="g2">
      <div class="fg"><label>Nome *</label><input id="cn" placeholder="Nome completo"></div>
      <div class="fg"><label>Data de nascimento</label><input id="cnas" type="date"></div>
      <div class="fg"><label>Empresa / Razão social</label><input id="ce" placeholder="Nome da empresa"></div>
      <div class="fg"><label>CPF / CNPJ</label><input id="cd" placeholder="000.000.000-00"></div>
    </div>
    <div class="sdiv">Contato</div>
    <div class="g2">
      <div class="fg"><label>WhatsApp *</label><input id="ct" placeholder="(83) 99999-9999"></div>
      <div class="fg"><label>E-mail</label><input id="cem" type="email" placeholder="email@exemplo.com"></div>
      <div class="fg"><label>Cidade / Estado</label><input id="cc" placeholder="Campina Grande / PB"></div>
      <div class="fg"><label>Endereço</label><input id="cend" placeholder="Rua, número, bairro"></div>
    </div>
    <div class="sdiv">Redes sociais</div>
    <div class="g2">
      <div class="fg"><label>Instagram</label><input id="cig" placeholder="@usuario"></div>
      <div class="fg"><label>Facebook</label><input id="cfb" placeholder="facebook.com/usuario"></div>
      <div class="fg"><label>TikTok</label><input id="ctt" placeholder="@usuario"></div>
      <div class="fg"><label>Site / Link</label><input id="csi" placeholder="https://seusite.com.br"></div>
    </div>
    <div class="sdiv">Configurações financeiras</div>
    <div class="g2">
      <div class="fg"><label>Desconto fixo (%)</label><input id="cdc" type="number" value="0" min="0" max="80" step="5"></div>
      <div class="fg"><label>Limite de fiado (R$)</label><input id="cfl" type="number" value="0" min="0" step="50" placeholder="0 = sem fiado"></div>
      <div class="fg s2"><label>Observações</label><textarea id="co" placeholder="Preferências, histórico, informações relevantes..."></textarea></div>
    </div>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-cli')">Cancelar</button><button class="btn pr" onclick="saveCliente()">Salvar cliente</button></div>
</div>
</div>

<!-- ══ MODAL ORÇAMENTO ══ -->
<div class="mbg" id="m-orc">
<div class="modal" style="width:650px">
  <div class="mh"><h2 id="mo-t">Novo orçamento</h2><button class="btn sm" onclick="closeM('m-orc')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div class="g2">
      <div class="fg"><label>Cliente</label><select id="oc" onchange="onCli()"></select></div>
      <div class="fg"><label>Nome da peça / projeto *</label><input id="on" placeholder="Ex: Suporte para câmera"></div>
      <div class="fg"><label>Impressora</label><select id="opr" onchange="calcM()"></select></div>
      <div class="fg"><label>Material</label><select id="om" oninput="calcM()"></select></div>
      <div class="fg"><label>Peso (g)</label><input id="ope" type="number" value="50" min="1" oninput="calcM()"></div>
      <div class="fg"><label>Tempo impressão (h)</label><input id="ot" type="number" value="4" step="0.5" oninput="calcM()"></div>
      <div class="fg"><label>Quantidade</label><input id="oq" type="number" value="1" min="1" oninput="calcM()"></div>
      <div class="fg"><label>Mão de obra (h)</label><input id="olh" type="number" value="0.5" step="0.25" oninput="calcM()"></div>
      <div class="fg"><label>Taxa por hora (R$)</label><input id="olr" type="number" value="40" step="5" oninput="calcM()"></div>
      <div class="fg"><label>Acabamento / extras (R$)</label><input id="oex" type="number" value="0" oninput="calcM()"></div>
      <div class="fg"><label>Frete (R$)</label><input id="ofr" type="number" value="0" oninput="calcM()"></div>
      <div class="fg"><label>Margem de lucro (%)</label><input id="omg" type="number" value="40" step="5" oninput="calcM()"></div>
      <div class="fg"><label>Impostos (%)</label><input id="otx" type="number" value="6" step="1" oninput="calcM()"></div>
      <div class="fg"><label>Desconto (%)</label><input id="odc" type="number" value="0" min="0" max="80" step="5" oninput="calcM()"></div>
      <div class="fg"><label>Status</label>
        <select id="ost"><option value="rascunho">Rascunho</option><option value="enviado">Enviado</option><option value="aprovado">Aprovado</option><option value="producao">Em produção</option><option value="entregue">Entregue</option><option value="cancelado">Cancelado</option></select>
      </div>
      <div class="fg"><label>Pagamento</label>
        <select id="opg" onchange="onPg()"><option value="pago">Pago à vista</option><option value="fiado">Fiado (a prazo)</option><option value="parcial">Entrada + saldo</option></select>
      </div>
      <div class="fg" id="ent-row" style="display:none"><label>Valor de entrada (R$)</label><input id="oent" type="number" value="0" min="0" step="10" oninput="calcM()"></div>
      <div class="fg s2"><label>Observações</label><textarea id="oob" placeholder="Cor, infill, detalhes..."></textarea></div>
    </div>
    <div class="sdiv">Resumo do cálculo</div>
    <div class="csec" id="mcalc"></div>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-orc')">Cancelar</button><button class="btn pr" onclick="saveOrc()">Salvar orçamento</button></div>
</div>
</div>

<!-- ══ MODAL FIADO MANUAL ══ -->
<div class="mbg" id="m-fiad-add">
<div class="modal" style="width:460px">
  <div class="mh"><h2 id="mfa-t">Adicionar fiado</h2><button class="btn sm" onclick="closeM('m-fiad-add')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div class="g2">
      <div class="fg s2"><label>Cliente *</label><select id="fa-cli"></select></div>
      <div class="fg s2"><label>Descrição *</label><input id="fa-desc" placeholder="Ex: Compra de peça avulsa, adiantamento..."></div>
      <div class="fg"><label>Valor (R$) *</label><input id="fa-val" type="number" step="0.01" min="0.01" placeholder="0,00"></div>
      <div class="fg"><label>Tipo</label>
        <select id="fa-tipo"><option value="debito">Débito (cliente deve)</option><option value="credito">Crédito (você deve)</option></select>
      </div>
      <div class="fg"><label>Vencimento (opcional)</label><input id="fa-venc" type="date"></div>
      <div class="fg"><label>Observação</label><input id="fa-obs" placeholder="Opcional"></div>
    </div>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-fiad-add')">Cancelar</button><button class="btn pr" onclick="saveFiadoManual()">Adicionar lançamento</button></div>
</div>
</div>

<!-- ══ MODAL RECEBER PAGAMENTO ══ -->
<div class="mbg" id="m-pag">
<div class="modal" style="width:440px">
  <div class="mh"><h2 id="mp-t">Registrar pagamento</h2><button class="btn sm" onclick="closeM('m-pag')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div id="mp-info" style="background:var(--sur2);border-radius:var(--rs);padding:11px;margin-bottom:14px;font-size:13px"></div>
    <div class="g2">
      <div class="fg s2"><label>Valor recebido (R$) *</label><input id="pv" type="number" step="0.01" min="0.01"></div>
      <div class="fg"><label>Forma de pagamento</label>
        <select id="pfp"><option>Pix</option><option>Dinheiro</option><option>Cartão débito</option><option>Cartão crédito</option><option>Transferência</option><option>Link de pagamento</option></select>
      </div>
      <div class="fg"><label>Data</label><input id="pdt" type="date"></div>
      <div class="fg s2"><label>Observação</label><input id="pob" placeholder="Opcional"></div>
    </div>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-pag')">Cancelar</button><button class="btn ok" onclick="savePag()">✓ Confirmar pagamento</button></div>
</div>
</div>

<!-- ══ MODAL PDF PREVIEW ══ -->
<div class="mbg" id="m-pdf">
<div class="modal" style="width:640px">
  <div class="mh"><h2>Visualizar orçamento</h2><button class="btn sm" onclick="closeM('m-pdf')" style="margin-left:auto">✕</button></div>
  <div class="mb" style="padding:0;background:#666;min-height:400px">
    <iframe id="pdf-fr" style="width:100%;height:520px;border:none;display:block"></iframe>
  </div>
  <div class="mf">
    <button class="btn" onclick="closeM('m-pdf')">Fechar</button>
    <button class="btn pr" onclick="dlPDF()">⬇ Baixar PDF</button>
    <button class="btn ok" style="background:#25D366;border-color:#25D366" onclick="wppSend()">📱 WhatsApp</button>
  </div>
</div>
</div>

<!-- ══ MODAL IMPRESSORA ══ -->
<div class="mbg" id="m-imp">
<div class="modal" style="width:500px">
  <div class="mh"><h2 id="mi-t">Nova impressora</h2><button class="btn sm" onclick="closeM('m-imp')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div class="g2">
      <div class="fg s2"><label>Nome / modelo *</label><input id="in" placeholder="Ex: Bambu Lab P1S"></div>
      <div class="fg"><label>Custo por hora (R$/h)</label><input id="ih" type="number" value="3.50" step="0.5" min="0"></div>
      <div class="fg"><label>Potência (W)</label><input id="ipw" type="number" value="150" step="10" min="0"></div>
      <div class="fg"><label>Volume máx. (mm)</label><input id="ivol" placeholder="220x220x250"></div>
      <div class="fg"><label>Tipo</label><select id="itp"><option>FDM</option><option>SLA/MSLA</option><option>SLS</option><option>Outro</option></select></div>
      <div class="fg s2"><label>Observações</label><input id="iob" placeholder="Multimaterial, câmera, etc."></div>
    </div>
    <label class="chk-row" style="margin-top:12px"><input type="checkbox" id="ipad"> Impressora padrão nos orçamentos</label>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-imp')">Cancelar</button><button class="btn pr" onclick="saveImp()">Salvar impressora</button></div>
</div>
</div>

<!-- ══ MODAL MATERIAL ══ -->
<div class="mbg" id="m-mat">
<div class="modal" style="width:420px">
  <div class="mh"><h2 id="mm-t">Novo material</h2><button class="btn sm" onclick="closeM('m-mat')" style="margin-left:auto">✕</button></div>
  <div class="mb">
    <div class="g2">
      <div class="fg"><label>Nome *</label><input id="mn" placeholder="Ex: PLA+ Silk Dourado"></div>
      <div class="fg"><label>Custo por grama (R$/g) *</label><input id="mp" type="number" step="0.01" min="0.01"></div>
      <div class="fg s2"><label>Descrição</label><input id="md" placeholder="Alta resistência, acabamento fosco..."></div>
    </div>
    <label class="chk-row" style="margin-top:12px"><input type="checkbox" id="mdef"> Material padrão nos novos orçamentos</label>
  </div>
  <div class="mf"><button class="btn" onclick="closeM('m-mat')">Cancelar</button><button class="btn pr" onclick="saveMat()">Salvar material</button></div>
</div>
</div>

<!-- ══ MODAL CONFIRMAR ══ -->
<div class="mbg" id="m-del">
<div class="modal" style="width:350px">
  <div class="mh"><h2 id="dl-t">Confirmar</h2></div>
  <div class="mb"><p id="dl-m" style="color:var(--mt);line-height:1.6;font-size:13px"></p></div>
  <div class="mf"><button class="btn" onclick="closeM('m-del')">Cancelar</button><button class="btn dg" id="dl-ok">Excluir</button></div>
</div>
</div>

<div id="toast"></div>

<script>
// ══════════════════════════════════════════════════════
// STATE
// ══════════════════════════════════════════════════════
const S={
  page:'dash',clientes:[],orcamentos:[],lancamentos:[],pagamentos:[],
  materiais:[
    {id:'m1',nome:'PLA',preco:0.08,desc:'Versátil, fácil de imprimir',padrao:true},
    {id:'m2',nome:'PETG',preco:0.10,desc:'Resistente à umidade',padrao:false},
    {id:'m3',nome:'ABS',preco:0.14,desc:'Alta temperatura',padrao:false},
    {id:'m4',nome:'TPU',preco:0.25,desc:'Flexível',padrao:false},
    {id:'m5',nome:'ASA',preco:0.35,desc:'UV-resistente',padrao:false},
    {id:'m6',nome:'Nylon',preco:0.50,desc:'Alta resistência',padrao:false}
  ],
  impressoras:[],
  cfg:{
    nomeLoja:'',whatsapp:'',email:'',site:'',instagram:'',facebook:'',
    localizacao:'',linkPagamento:'',pix:'',pixTipo:'chave',
    assinatura:'Qualquer dúvida, estou à disposição! 😊',
    logoBase64:'',qrcodeBase64:'',
    maqCusto:3.50,maqPotencia:150,energia:0.90,laborRate:40,margem:40,imposto:6,falha:5,
    pdfMostrar:{material:true,peso:true,tempo:true,qty:true,labor:true,extras:true,margem:false,imposto:false,desconto:true,subtotal:true,unitario:true},
    pdfPagamentos:{pix:true,cartao:true,dinheiro:true,link:false,qrcode:true}
  },
  editC:null,editO:null,editMat:null,editImp:null,detailId:null,
  driveOk:false,token:null,fileId:null,clientId:null,
  _pdf:null,_pdfOrcId:null,_pagCid:null,_pagOrcId:null,_pagLancId:null
};

// ══════════════════════════════════════════════════════
// HELPERS
// ══════════════════════════════════════════════════════
const R=v=>'R$ '+Number(v||0).toLocaleString('pt-BR',{minimumFractionDigits:2,maximumFractionDigits:2});
const dt=ts=>ts?new Date(ts).toLocaleDateString('pt-BR'):'—';
const uid=()=>Date.now().toString(36)+Math.random().toString(36).slice(2,5);
const vv=id=>document.getElementById(id)?.value.trim()||'';
const gn=id=>+(document.getElementById(id)?.value||0);
const badge=(cls,lbl)=>`<span class="badge ${cls}">${lbl}</span>`;
const STATUS={rascunho:['gy','Rascunho'],enviado:['bl','Enviado'],aprovado:['gn','Aprovado'],producao:['wn','Em produção'],entregue:['gn','Entregue'],cancelado:['rd','Cancelado']};
const bSt=s=>{const[c,l]=STATUS[s]||['gy',s];return badge(c,l)};
const matName=p=>{const m=S.materiais.find(x=>x.preco==p);return m?m.nome:'Material'};
const matOpts=(sel)=>S.materiais.map(m=>`<option value="${m.preco}"${m.preco==sel||(sel===undefined&&m.padrao)?'selected':''}>${m.nome} (R$ ${m.preco.toFixed(2)}/g)</option>`).join('');
const prOpts=(sel)=>`<option value="">— Padrão global —</option>`+S.impressoras.map(p=>`<option value="${p.id}"${p.id===sel||(sel===undefined&&p.padrao)?'selected':''}>${p.nome}</option>`).join('');
const defMat=()=>S.materiais.find(m=>m.padrao)||S.materiais[0]||{preco:0.08};
const defPrinter=()=>S.impressoras.find(p=>p.padrao)||null;
const openM=id=>document.getElementById(id).classList.add('open');
const closeM=id=>document.getElementById(id).classList.remove('open');
const toast=(msg,t=3200)=>{const el=document.getElementById('toast');el.textContent=msg;el.classList.add('show');clearTimeout(el._t);el._t=setTimeout(()=>el.classList.remove('show'),t)};
document.querySelectorAll('.mbg').forEach(bg=>bg.addEventListener('click',e=>{if(e.target===bg)bg.classList.remove('open')}));

// ══════════════════════════════════════════════════════
// FIADO SALDO
// ══════════════════════════════════════════════════════
function fiadoSaldo(cid){
  const fromOrcs=S.orcamentos.filter(o=>o.clienteId===cid&&(o.pagamento==='fiado'||o.pagamento==='parcial')).reduce((s,o)=>s+(o.saldoDevedor||0),0);
  const fromLanc=S.lancamentos.filter(l=>l.clienteId===cid).reduce((s,l)=>s+(l.tipo==='debito'?l.valor:-l.valor),0);
  return Math.max(0,fromOrcs+fromLanc);
}
function aniversariantesHoje(){
  const hoje=new Date();const md=`${String(hoje.getMonth()+1).padStart(2,'0')}-${String(hoje.getDate()).padStart(2,'0')}`;
  return S.clientes.filter(c=>c.nascimento&&c.nascimento.slice(5)===md);
}

// ══════════════════════════════════════════════════════
// GOOGLE DRIVE
// ══════════════════════════════════════════════════════
function initDrive(){
  if(!window.google){setTimeout(initDrive,600);return}
  try{S.tc=google.accounts.oauth2.initTokenClient({
    client_id:S.clientId||'',scope:'https://www.googleapis.com/auth/drive.file',
    callback:async r=>{
      if(r.error){toast('Erro Drive: '+r.error);return}
      S.token=r.access_token;S.driveOk=true;
      document.getElementById('ddot').className='dr-dot ok';
      document.getElementById('dtext').textContent='Drive conectado';
      localStorage.setItem('p3d_cid',S.clientId);
      await loadDrive();renderPage();toast('✓ Google Drive conectado!');
    }
  })}catch(e){}
}
function connectDrive(){
  if(!S.clientId){
    const cid=prompt('Cole seu Google OAuth Client ID:\n(console.cloud.google.com → APIs → Credenciais → OAuth 2.0 → Aplicativo da Web)\n\nOrigens permitidas: '+location.origin);
    if(!cid||!cid.includes('.apps.'))return toast('Client ID inválido');
    S.clientId=cid;initDrive();setTimeout(()=>S.tc?.requestAccessToken({prompt:'consent'}),800);return;
  }
  S.tc?.requestAccessToken();
}
async function driveReq(method,ep,body){
  const r=await fetch('https://www.googleapis.com/'+ep,{method,headers:{'Authorization':'Bearer '+S.token,'Content-Type':'application/json'},body:body?JSON.stringify(body):undefined});
  if(r.status===401){S.driveOk=false;document.getElementById('ddot').className='dr-dot';document.getElementById('dtext').textContent='Sessão expirada';return null}
  return r.ok?r.json():null;
}
async function loadDrive(){
  const list=await driveReq('GET',`drive/v3/files?q=name='print3d_dados.json' and trashed=false&fields=files(id,name)`);
  if(!list?.files?.length){await saveDrive();return}
  S.fileId=list.files[0].id;
  const r=await fetch(`https://www.googleapis.com/drive/v3/files/${S.fileId}?alt=media`,{headers:{'Authorization':'Bearer '+S.token}});
  if(!r.ok)return;
  const d=await r.json();
  S.clientes=d.clientes||[];S.orcamentos=d.orcamentos||[];
  S.lancamentos=d.lancamentos||[];S.pagamentos=d.pagamentos||[];
  if(d.materiais?.length)S.materiais=d.materiais;
  if(d.impressoras)S.impressoras=d.impressoras;
  if(d.cfg)S.cfg=Object.assign({},S.cfg,d.cfg);
  toast('✓ Dados carregados do Drive!');
}
async function saveDrive(){
  if(!S.driveOk){saveLocal();return}
  document.getElementById('saving').style.display='flex';
  const payload={clientes:S.clientes,orcamentos:S.orcamentos,lancamentos:S.lancamentos,pagamentos:S.pagamentos,materiais:S.materiais,impressoras:S.impressoras,cfg:S.cfg,ts:Date.now()};
  const blob=new Blob([JSON.stringify(payload)],{type:'application/json'});
  const form=new FormData();
  form.append('metadata',new Blob([JSON.stringify({name:'print3d_dados.json',mimeType:'application/json'})],{type:'application/json'}));
  form.append('file',blob);
  const url=S.fileId?`https://www.googleapis.com/upload/drive/v3/files/${S.fileId}?uploadType=multipart`:'https://www.googleapis.com/upload/drive/v3/files?uploadType=multipart';
  const res=await fetch(url,{method:S.fileId?'PATCH':'POST',headers:{'Authorization':'Bearer '+S.token},body:form});
  if(res.ok&&!S.fileId){const d=await res.json();S.fileId=d.id}
  document.getElementById('saving').style.display='none';saveLocal();
}
function saveLocal(){try{localStorage.setItem('p3d_v4',JSON.stringify({clientes:S.clientes,orcamentos:S.orcamentos,lancamentos:S.lancamentos,pagamentos:S.pagamentos,materiais:S.materiais,impressoras:S.impressoras,cfg:S.cfg}))}catch(e){}}
function loadLocal(){
  try{const d=JSON.parse(localStorage.getItem('p3d_v4')||'{}');
    S.clientes=d.clientes||[];S.orcamentos=d.orcamentos||[];
    S.lancamentos=d.lancamentos||[];S.pagamentos=d.pagamentos||[];
    if(d.materiais?.length)S.materiais=d.materiais;
    if(d.impressoras)S.impressoras=d.impressoras;
    if(d.cfg)S.cfg=Object.assign({},S.cfg,d.cfg);
  }catch(e){}
  const cid=localStorage.getItem('p3d_cid');if(cid)S.clientId=cid;
}

// ══════════════════════════════════════════════════════
// NAVIGATION
// ══════════════════════════════════════════════════════
function nav(page,id){
  S.page=page;S.detailId=id||null;
  document.querySelectorAll('.ni').forEach(el=>el.classList.remove('active'));
  ['dash','cli','orc','fia','calc','cfg'].forEach((p,i)=>{if(p===page)document.querySelectorAll('.ni')[i]?.classList.add('active')});
  renderPage();
}
function renderPage(){
  const T={dash:'Dashboard',cli:'Clientes',orc:'Orçamentos',fia:'Fiado / Crédito',calc:'Calculadora',cfg:'Configurações',cdet:'Detalhes do cliente'};
  document.getElementById('ptitle').textContent=T[S.page]||'';
  const c=document.getElementById('content'),a=document.getElementById('tact');
  a.innerHTML='';
  if(S.page==='dash')c.innerHTML=rDash();
  else if(S.page==='cli'){c.innerHTML=rCli();a.innerHTML='<button class="btn pr" onclick="openCli()">+ Novo cliente</button>'}
  else if(S.page==='orc'){c.innerHTML=rOrcs();a.innerHTML='<button class="btn pr" onclick="openOrc()">+ Novo orçamento</button>'}
  else if(S.page==='fia'){c.innerHTML=rFiado();a.innerHTML='<button class="btn wn" onclick="openFiadoManual()">+ Lançamento manual</button><button class="btn pr" onclick="openOrc()">+ Orçamento fiado</button>'}
  else if(S.page==='calc'){c.innerHTML=rCalc();calcSC()}
  else if(S.page==='cfg')c.innerHTML=rCfg();
  else if(S.page==='cdet'){c.innerHTML=rCDet();a.innerHTML=`<button class="btn" onclick="nav('cli')">← Voltar</button><button class="btn pr" onclick="openOrc('${S.detailId}')">+ Orçamento</button>`}
}

// ══════════════════════════════════════════════════════
// DASHBOARD
// ══════════════════════════════════════════════════════
function rDash(){
  const fat=S.orcamentos.filter(o=>['aprovado','entregue'].includes(o.status)).reduce((s,o)=>s+(o.total||0),0);
  const pend=S.orcamentos.filter(o=>['enviado','rascunho'].includes(o.status)).length;
  const totalFiado=S.clientes.reduce((s,c)=>s+fiadoSaldo(c.id),0);
  const aniv=aniversariantesHoje();
  const rec=[...S.orcamentos].sort((a,b)=>b.criado-a.criado).slice(0,5);
  return`${!S.driveOk?`<div class="banner">⚠️<span style="flex:1">Dados salvos apenas localmente. <strong>Conecte o Google Drive</strong> para não perder nada.</span><button class="btn sm" onclick="connectDrive()">Conectar</button></div>`:''}
  ${aniv.length?`<div class="banner" style="background:var(--okb);border-color:#8ed4b0">🎂 <span>Aniversário hoje: <strong>${aniv.map(c=>c.nome.split(' ')[0]).join(', ')}</strong>! ${aniv[0]?.tel?`<button class="btn sm" onclick="wppAniv('${aniv[0].id}')" style="margin-left:8px">📱 Parabenizar</button>`:''}</span></div>`:''}
  <div class="sc">
    <div class="scard"><div class="sl">Clientes</div><div class="sv">${S.clientes.length}</div><div class="ss">cadastrados</div></div>
    <div class="scard"><div class="sl">Faturamento</div><div class="sv" style="font-size:16px">${R(fat)}</div><div class="ss">aprovados+entregues</div></div>
    <div class="scard"><div class="sl">Pendentes</div><div class="sv">${pend}</div><div class="ss">aguardando resposta</div></div>
    <div class="scard" style="${totalFiado>0?'border-color:#f0d080;background:var(--wnb)':''}"><div class="sl">Total em fiado</div><div class="sv" style="font-size:16px;${totalFiado>0?'color:var(--wn)':''}">${R(totalFiado)}</div><div class="ss">a receber</div></div>
  </div>
  <div class="tw"><div class="th2"><span class="ttl">Orçamentos recentes</span><button class="btn sm" onclick="nav('orc')">Ver todos</button></div>
    ${rec.length?`<table><thead><tr><th>Projeto</th><th>Cliente</th><th>Status</th><th>Pagamento</th><th>Valor</th><th>Data</th></tr></thead><tbody>
    ${rec.map(o=>{const cl=S.clientes.find(c=>c.id===o.clienteId);return`<tr style="cursor:pointer" onclick="nav('orc')">
      <td><strong>${o.nome}</strong></td><td>${cl?cl.nome:'—'}</td><td>${bSt(o.status)}</td>
      <td>${bPg(o.pagamento,o.saldoDevedor)}</td>
      <td style="font-family:'DM Mono',monospace;font-weight:500;color:var(--ac)">${R(o.total)}</td>
      <td style="color:var(--mt)">${dt(o.criado)}</td></tr>`}).join('')}</tbody></table>`
    :`<div class="empty"><div class="ei">◎</div><p>Nenhum orçamento ainda</p><button class="btn pr" onclick="openOrc()">Criar primeiro orçamento</button></div>`}
  </div>`;
}
function bPg(pg,saldo){
  if(pg==='fiado')return saldo>0?badge('rd','Fiado '+R(saldo)):badge('gn','Fiado quitado');
  if(pg==='parcial')return saldo>0?badge('wn','Parcial '+R(saldo)):badge('gn','Quitado');
  return badge('gn','Pago');
}
function wppAniv(cid){
  const c=S.clientes.find(x=>x.id===cid);if(!c)return;
  const tel=c.tel?.replace(/\D/g,'');
  const msg=encodeURIComponent(`Olá, ${c.nome.split(' ')[0]}! 🎉🎂 Tudo bem?\n\nPassando para desejar um feliz aniversário! Que seja um dia incrível!\n\n${S.cfg.nomeLoja||'Print3D Manager'}`);
  window.open(`https://wa.me/55${tel}?text=${msg}`,'_blank');
}

// ══════════════════════════════════════════════════════
// CLIENTES
// ══════════════════════════════════════════════════════
function rCli(list){
  list=list||S.clientes;
  return`<div class="tw"><div class="th2"><span class="ttl">Clientes (${S.clientes.length})</span>
    <input class="srch" placeholder="Buscar..." oninput="filtC(this.value)"></div>
    <div id="ctb">${rCliRows(list)}</div></div>`;
}
function rCliRows(list){
  if(!list.length)return`<div class="empty"><div class="ei">◉</div><p>Nenhum cliente</p><button class="btn pr" onclick="openCli()">+ Novo cliente</button></div>`;
  const hoje=new Date();
  return`<table><thead><tr><th>Nome</th><th>Contato</th><th>Nascimento</th><th>Desconto</th><th>Fiado</th><th>Ações</th></tr></thead><tbody>
  ${list.map(c=>{
    const saldo=fiadoSaldo(c.id);const limite=c.fiadoLimite||0;
    const pct=limite>0?Math.min(100,(saldo/limite)*100):0;
    const ini=c.nome.split(' ').map(w=>w[0]).slice(0,2).join('').toUpperCase();
    let anivStr='',anivAlert=false;
    if(c.nascimento){
      const n=new Date(c.nascimento+'T00:00:00');
      anivStr=`${String(n.getDate()).padStart(2,'0')}/${String(n.getMonth()+1).padStart(2,'0')}`;
      anivAlert=n.getMonth()===hoje.getMonth()&&n.getDate()===hoje.getDate();
    }
    return`<tr><td><div style="display:flex;align-items:center;gap:9px;cursor:pointer" onclick="nav('cdet','${c.id}')">
      <div class="av" style="width:33px;height:33px;font-size:12px">${ini}</div>
      <div><div style="font-weight:500">${c.nome}</div>${c.empresa?`<div style="font-size:11px;color:var(--mt)">${c.empresa}</div>`:''}</div></div></td>
    <td style="font-size:12px">${c.tel?`<div>${c.tel}</div>`:''}${c.email?`<div style="color:var(--mt)">${c.email}</div>`:''}</td>
    <td>${anivStr?`<span style="font-size:12px${anivAlert?';color:var(--ok);font-weight:600':''}">🎂 ${anivStr}</span>`:'—'}</td>
    <td>${c.desconto?badge('gn',c.desconto+'%'):'—'}</td>
    <td style="min-width:110px">${saldo>0?`<div style="font-size:12px;font-weight:600;color:var(--wn)">${R(saldo)}</div>${limite>0?`<div class="pb"><div class="pf" style="width:${pct}%;background:${pct>=90?'var(--dg)':'var(--wn)'}"></div></div>`:''}`:'—'}</td>
    <td><div style="display:flex;gap:4px">
      <button class="btn sm" onclick="nav('cdet','${c.id}')">Ver</button>
      <button class="btn sm" onclick="openCli('${c.id}')">Editar</button>
      <button class="btn sm dg" onclick="confDel('cli','${c.id}')">✕</button>
    </div></td></tr>`;
  }).join('')}</tbody></table>`;
}
function filtC(q){const f=S.clientes.filter(c=>(c.nome+c.empresa+c.email+c.tel).toLowerCase().includes(q.toLowerCase()));document.getElementById('ctb').innerHTML=rCliRows(f)}

// ══════════════════════════════════════════════════════
// DETALHE CLIENTE
// ══════════════════════════════════════════════════════
function rCDet(){
  const c=S.clientes.find(x=>x.id===S.detailId);if(!c)return'';
  const orcs=S.orcamentos.filter(o=>o.clienteId===c.id).sort((a,b)=>b.criado-a.criado);
  const lancs=S.lancamentos.filter(l=>l.clienteId===c.id).sort((a,b)=>b.ts-a.ts);
  const fat=orcs.filter(o=>['aprovado','entregue'].includes(o.status)).reduce((s,o)=>s+o.total,0);
  const saldo=fiadoSaldo(c.id);
  const ini=c.nome.split(' ').map(w=>w[0]).slice(0,2).join('').toUpperCase();
  const redes=[c.instagram&&`<a href="https://instagram.com/${c.instagram.replace('@','')}" target="_blank" style="color:var(--ac);font-size:12px">📷 ${c.instagram}</a>`,
    c.facebook&&`<a href="${c.facebook.startsWith('http')?c.facebook:'https://'+c.facebook}" target="_blank" style="color:var(--ac);font-size:12px">📘 Facebook</a>`,
    c.site&&`<a href="${c.site}" target="_blank" style="color:var(--ac);font-size:12px">🌐 Site</a>`].filter(Boolean);
  return`<div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:18px;margin-bottom:14px;display:flex;align-items:flex-start;gap:15px;flex-wrap:wrap">
    <div class="av" style="width:52px;height:52px;font-size:18px">${ini}</div>
    <div style="flex:1;min-width:200px">
      <div style="font-size:17px;font-weight:600">${c.nome}${c.nascimento?` <span style="font-size:12px;color:var(--mt)">🎂 ${new Date(c.nascimento+'T00:00:00').toLocaleDateString('pt-BR',{day:'2-digit',month:'long'})}</span>`:''}</div>
      <div style="font-size:13px;color:var(--mt)">${[c.empresa,c.cidade].filter(Boolean).join(' · ')}</div>
      <div style="display:flex;gap:12px;margin-top:6px;font-size:12px;color:var(--mt);flex-wrap:wrap">
        ${c.email?`<span>✉ ${c.email}</span>`:''}${c.tel?`<span>📱 ${c.tel}</span>`:''}${c.doc?`<span>📄 ${c.doc}</span>`:''}
        ${c.desconto?`<span style="color:var(--ok);font-weight:500">🏷 ${c.desconto}% desconto</span>`:''}
      </div>
      ${redes.length?`<div style="display:flex;gap:10px;margin-top:6px;flex-wrap:wrap">${redes.join('')}</div>`:''}
    </div>
    <div style="display:flex;flex-direction:column;gap:8px;align-items:flex-end">
      <div style="text-align:right"><div style="font-size:11px;color:var(--mt)">Faturamento</div><div style="font-family:'DM Mono',monospace;font-size:19px;font-weight:600;color:var(--ac)">${R(fat)}</div></div>
      ${saldo>0?`<div style="background:var(--wnb);border:1px solid #f0d080;border-radius:var(--rs);padding:7px 11px;text-align:center"><div style="font-size:11px;color:var(--wn)">Em aberto</div><div style="font-family:'DM Mono',monospace;font-size:15px;font-weight:600;color:var(--wn)">${R(saldo)}</div></div>`:''}
      <div style="display:flex;gap:6px;flex-wrap:wrap">
        <button class="btn sm" onclick="openCli('${c.id}')">Editar</button>
        ${c.tel?`<button class="btn sm ok" onclick="wppAniv('${c.id}')">📱 WPP</button>`:''}
        ${saldo>0?`<button class="btn sm wn" onclick="openPagCli('${c.id}')">💰 Receber</button>`:''}
      </div>
    </div>
  </div>
  ${c.obs?`<div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:12px 16px;margin-bottom:14px;font-size:13px;color:var(--mt)">${c.obs}</div>`:''}
  <div style="font-size:14px;font-weight:600;margin-bottom:10px">Orçamentos (${orcs.length})</div>
  ${orcs.length?orcs.map(o=>`<div class="qcard">
    <div style="flex:1;min-width:0"><div style="font-weight:500">${o.nome}</div>
    <div style="font-size:12px;color:var(--mt)">${o.material}·${o.peso}g·${o.qty}x·${dt(o.criado)}${o.desconto?` · <span style="color:var(--ok)">-${o.desconto}% desc.</span>`:''}</div></div>
    ${bSt(o.status)} ${bPg(o.pagamento,o.saldoDevedor)}
    <div style="font-family:'DM Mono',monospace;font-size:15px;font-weight:500;color:var(--ac)">${R(o.total)}</div>
    <div style="display:flex;gap:4px;flex-wrap:wrap">
      ${(o.pagamento==='fiado'||o.pagamento==='parcial')&&o.saldoDevedor>0?`<button class="btn sm wn" onclick="openPagOrc('${o.id}')">💰</button>`:''}
      <button class="btn sm pr" onclick="gerarPDF('${o.id}')">📄</button>
      <button class="btn sm" onclick="openOrcEdit('${o.id}')">✏</button>
      <button class="btn sm dg" onclick="confDel('orc','${o.id}')">✕</button>
    </div></div>`).join(''):`<div class="empty" style="padding:30px 0"><p>Nenhum orçamento</p><button class="btn pr" onclick="openOrc('${c.id}')">+ Criar</button></div>`}
  ${lancs.length?`<div style="font-size:14px;font-weight:600;margin:16px 0 10px">Lançamentos manuais (${lancs.length})</div>
  ${lancs.map(l=>`<div class="qcard" style="${l.tipo==='debito'?'border-color:#f8c9c9':'border-color:#8ed4b0'}">
    <div style="flex:1"><div style="font-weight:500">${l.desc}</div><div style="font-size:11px;color:var(--mt)">${dt(l.ts)}${l.venc?` · Venc: ${dt(new Date(l.venc+'T00:00:00').getTime())}`:''}</div></div>
    <span style="font-family:'DM Mono',monospace;font-weight:600;color:${l.tipo==='debito'?'var(--dg)':'var(--ok)'}">${l.tipo==='debito'?'+':'-'}${R(l.valor)}</span>
    <button class="btn sm dg" onclick="confDel('lanc','${l.id}')">✕</button>
  </div>`).join('')}`:''}`;
}

// ══════════════════════════════════════════════════════
// ORÇAMENTOS
// ══════════════════════════════════════════════════════
function rOrcs(list){
  list=list||[...S.orcamentos].sort((a,b)=>b.criado-a.criado);
  return`<div class="tw"><div class="th2"><span class="ttl">Orçamentos (${S.orcamentos.length})</span>
    <select style="font-size:13px;padding:5px 9px;border:1px solid var(--bdr);border-radius:var(--rs);background:var(--bg)" onchange="filtO(this.value)">
      <option value="">Todos</option><option>rascunho</option><option>enviado</option><option>aprovado</option><option>producao</option><option>entregue</option><option>cancelado</option>
    </select></div><div id="otb">${rOrcRows(list)}</div></div>`;
}
function rOrcRows(list){
  if(!list.length)return`<div class="empty"><div class="ei">◎</div><p>Nenhum orçamento</p><button class="btn pr" onclick="openOrc()">+ Novo</button></div>`;
  return`<table><thead><tr><th>Projeto</th><th>Cliente</th><th>Mat.</th><th>Desconto</th><th>Pagamento</th><th>Total</th><th>Status</th><th>Ações</th></tr></thead><tbody>
  ${list.map(o=>{const cl=S.clientes.find(c=>c.id===o.clienteId);return`<tr>
    <td><strong>${o.nome}</strong></td>
    <td style="cursor:pointer;color:var(--ac)" onclick="${cl?`nav('cdet','${cl.id}')`:'void(0)'}">${cl?cl.nome:'—'}</td>
    <td>${badge('gy',o.material||'PLA')}</td>
    <td>${o.desconto?badge('gn','-'+o.desconto+'%'):'—'}</td>
    <td>${bPg(o.pagamento,o.saldoDevedor)}</td>
    <td style="font-family:'DM Mono',monospace;font-weight:500;color:var(--ac)">${R(o.total)}</td>
    <td>${bSt(o.status)}</td>
    <td><div style="display:flex;gap:4px;flex-wrap:wrap">
      ${(o.pagamento==='fiado'||o.pagamento==='parcial')&&o.saldoDevedor>0?`<button class="btn sm wn" onclick="openPagOrc('${o.id}')">💰</button>`:''}
      <button class="btn sm pr" onclick="gerarPDF('${o.id}')">📄</button>
      <button class="btn sm" onclick="openOrcEdit('${o.id}')">✏</button>
      <button class="btn sm dg" onclick="confDel('orc','${o.id}')">✕</button>
    </div></td></tr>`}).join('')}</tbody></table>`;
}
function filtO(v){const f=v?S.orcamentos.filter(o=>o.status===v):S.orcamentos;document.getElementById('otb').innerHTML=rOrcRows(f.sort((a,b)=>b.criado-a.criado))}

// ══════════════════════════════════════════════════════
// FIADO
// ══════════════════════════════════════════════════════
function rFiado(){
  const comFiado=S.clientes.filter(c=>fiadoSaldo(c.id)>0);
  const total=comFiado.reduce((s,c)=>s+fiadoSaldo(c.id),0);
  const pags=[...S.pagamentos].sort((a,b)=>b.ts-a.ts).slice(0,10);
  return`<div class="sc">
    <div class="scard" style="${total>0?'border-color:#f0d080;background:var(--wnb)':''}"><div class="sl">Total em aberto</div><div class="sv" style="font-size:17px;${total>0?'color:var(--wn)':''}">${R(total)}</div><div class="ss">${comFiado.length} cliente(s)</div></div>
    <div class="scard"><div class="sl">Recebido (histórico)</div><div class="sv" style="font-size:17px">${R(S.pagamentos.reduce((s,p)=>s+p.valor,0))}</div><div class="ss">total de pagamentos</div></div>
    <div class="scard"><div class="sl">Lançamentos manuais</div><div class="sv">${S.lancamentos.length}</div><div class="ss">débitos e créditos</div></div>
    <div class="scard"><div class="sl">Clientes em dia</div><div class="sv">${S.clientes.filter(c=>fiadoSaldo(c.id)===0).length}</div><div class="ss">sem pendências</div></div>
  </div>
  <div style="display:grid;grid-template-columns:1fr 1fr;gap:16px">
  <div>
    <div style="font-size:14px;font-weight:600;margin-bottom:10px">Clientes com saldo em aberto</div>
    ${comFiado.length?comFiado.sort((a,b)=>fiadoSaldo(b.id)-fiadoSaldo(a.id)).map(c=>{
      const saldo=fiadoSaldo(c.id);const limite=c.fiadoLimite||0;
      const pct=limite>0?Math.min(100,(saldo/limite)*100):0;
      const alerta=limite>0&&pct>=90;
      return`<div class="fc ${alerta?'dg':pct>=70?'wn':''}">
        <div style="display:flex;align-items:center;gap:9px;margin-bottom:7px">
          <div class="av" style="width:30px;height:30px;font-size:11px">${c.nome.split(' ').map(w=>w[0]).slice(0,2).join('').toUpperCase()}</div>
          <div style="flex:1"><div style="font-weight:500;font-size:13px">${c.nome}</div>${c.tel?`<div style="font-size:11px;color:var(--mt)">${c.tel}</div>`:''}</div>
          <div style="font-family:'DM Mono',monospace;font-weight:600;font-size:15px;color:${alerta?'var(--dg)':'var(--wn)'}">${R(saldo)}</div>
        </div>
        ${limite>0?`<div class="pb"><div class="pf" style="width:${pct}%;background:${pct>=90?'var(--dg)':'var(--wn)'}"></div></div><div style="font-size:10px;color:var(--mt);margin-top:3px">${R(saldo)} / ${R(limite)} (${Math.round(pct)}%)</div>`:''}
        <div style="display:flex;gap:5px;margin-top:9px;flex-wrap:wrap">
          <button class="btn sm wn" onclick="openPagCli('${c.id}')">💰 Receber</button>
          <button class="btn sm pr" onclick="openFiadoManual('${c.id}')">+ Lançamento</button>
          <button class="btn sm" onclick="nav('cdet','${c.id}')">Ver detalhes</button>
          ${c.tel?`<button class="btn sm ok" style="background:#25D366;border-color:#25D366;color:#fff" onclick="wppCobrar('${c.id}')">📱 Cobrar</button>`:''}
        </div>
      </div>`;}).join(''):`<div class="empty" style="padding:35px 0"><p>Nenhum cliente com saldo!</p></div>`}
  </div>
  <div>
    <div style="font-size:14px;font-weight:600;margin-bottom:10px">Últimos pagamentos</div>
    ${pags.length?`<div class="tw"><table><thead><tr><th>Cliente</th><th>Valor</th><th>Forma</th><th>Data</th></tr></thead><tbody>
    ${pags.map(p=>{const cl=S.clientes.find(c=>c.id===p.clienteId);return`<tr>
      <td>${cl?cl.nome:'—'}</td>
      <td style="font-family:'DM Mono',monospace;color:var(--ok);font-weight:500">${R(p.valor)}</td>
      <td>${badge('gn',p.forma)}</td>
      <td style="color:var(--mt)">${dt(p.ts)}</td></tr>`;}).join('')}</tbody></table></div>`
    :`<div class="empty" style="padding:35px 0"><p>Nenhum pagamento registrado</p></div>`}
  </div>
  </div>`;
}
function openFiadoManual(cid){
  const sel=document.getElementById('fa-cli');
  sel.innerHTML='<option value="">Selecione...</option>'+S.clientes.map(c=>`<option value="${c.id}">${c.nome}</option>`).join('');
  if(cid)sel.value=cid;
  document.getElementById('fa-desc').value='';document.getElementById('fa-val').value='';
  document.getElementById('fa-obs').value='';document.getElementById('fa-venc').value='';
  document.getElementById('fa-tipo').value='debito';
  openM('m-fiad-add');
}
function saveFiadoManual(){
  const cid=document.getElementById('fa-cli').value;
  const desc=vv('fa-desc');const val=parseFloat(document.getElementById('fa-val').value);
  if(!cid)return toast('⚠ Selecione um cliente');
  if(!desc)return toast('⚠ Informe a descrição');
  if(!val||val<=0)return toast('⚠ Informe um valor válido');
  S.lancamentos.push({id:uid(),clienteId:cid,desc,valor:val,tipo:document.getElementById('fa-tipo').value,
    venc:document.getElementById('fa-venc').value,obs:vv('fa-obs'),ts:Date.now()});
  closeM('m-fiad-add');saveDrive();toast('✓ Lançamento adicionado!');renderPage();
}
function openPagCli(cid){
  const saldo=fiadoSaldo(cid);const cl=S.clientes.find(c=>c.id===cid);
  S._pagCid=cid;S._pagOrcId=null;S._pagLancId=null;
  document.getElementById('mp-t').textContent='Receber pagamento';
  document.getElementById('mp-info').innerHTML=`Cliente: <strong>${cl?.nome||'—'}</strong><br>Total em aberto: <strong style="color:var(--wn)">${R(saldo)}</strong>`;
  document.getElementById('pv').value=saldo.toFixed(2);
  document.getElementById('pob').value='';document.getElementById('pdt').value=new Date().toISOString().slice(0,10);
  openM('m-pag');
}
function openPagOrc(orcId){
  const o=S.orcamentos.find(x=>x.id===orcId);if(!o)return;
  const cl=S.clientes.find(c=>c.id===o.clienteId);
  S._pagCid=o.clienteId;S._pagOrcId=orcId;S._pagLancId=null;
  document.getElementById('mp-t').textContent='Receber pagamento do orçamento';
  document.getElementById('mp-info').innerHTML=`<strong>${o.nome}</strong><br>Cliente: ${cl?.nome||'—'}<br>Saldo: <strong style="color:var(--wn)">${R(o.saldoDevedor)}</strong>`;
  document.getElementById('pv').value=(o.saldoDevedor||0).toFixed(2);
  document.getElementById('pob').value='';document.getElementById('pdt').value=new Date().toISOString().slice(0,10);
  openM('m-pag');
}
function savePag(){
  const valor=parseFloat(document.getElementById('pv').value);
  if(!valor||valor<=0)return toast('⚠ Valor inválido');
  const forma=document.getElementById('pfp').value;
  const obs=vv('pob');const pdt=document.getElementById('pdt').value;
  if(S._pagOrcId){
    const o=S.orcamentos.find(x=>x.id===S._pagOrcId);
    if(o)o.saldoDevedor=Math.max(0,(o.saldoDevedor||0)-valor);
  } else if(S._pagCid){
    let rest=valor;
    S.orcamentos.filter(o=>o.clienteId===S._pagCid&&o.saldoDevedor>0).sort((a,b)=>a.criado-b.criado).forEach(o=>{
      if(rest<=0)return;const ab=Math.min(o.saldoDevedor,rest);o.saldoDevedor=Math.max(0,o.saldoDevedor-ab);rest-=ab;
    });
    S.lancamentos.filter(l=>l.clienteId===S._pagCid&&l.tipo==='debito').sort((a,b)=>a.ts-b.ts).forEach(l=>{
      if(rest<=0)return;const ab=Math.min(l.valor,rest);l.valor=Math.max(0,l.valor-ab);rest-=ab;
    });
  }
  S.pagamentos.push({id:uid(),clienteId:S._pagCid,orcId:S._pagOrcId,valor,forma,obs,ts:pdt?new Date(pdt+'T12:00:00').getTime():Date.now()});
  closeM('m-pag');saveDrive();toast(`✓ Pagamento de ${R(valor)} registrado!`);renderPage();
}
function wppCobrar(cid){
  const c=S.clientes.find(x=>x.id===cid);const saldo=fiadoSaldo(cid);
  const tel=c?.tel?.replace(/\D/g,'');const loja=S.cfg.nomeLoja||'nossa loja';
  const pix=S.cfg.pix?`\n\n💳 Chave Pix: *${S.cfg.pix}*`:'';
  const link=S.cfg.linkPagamento?`\n🔗 Link de pagamento: ${S.cfg.linkPagamento}`:'';
  const msg=encodeURIComponent(`Olá, ${c?.nome?.split(' ')[0]||''}! Tudo bem? 😊\n\nPassando para avisar que você tem um saldo em aberto de *${R(saldo)}* aqui em ${loja}.${pix}${link}\n\nQualquer dúvida, estou à disposição!`);
  window.open(`https://wa.me/55${tel}?text=${msg}`,'_blank');
}

// ══════════════════════════════════════════════════════
// MODAL CLIENTE
// ══════════════════════════════════════════════════════
function openCli(id){
  S.editC=id||null;
  document.getElementById('mc-t').textContent=id?'Editar cliente':'Novo cliente';
  const c=id?S.clientes.find(x=>x.id===id):{};
  ['cn','ce','cd','ct','cem','cc','cend','cig','cfb','ctt','csi','co'].forEach(i=>document.getElementById(i).value=c[{cn:'nome',ce:'empresa',cd:'doc',ct:'tel',cem:'email',cc:'cidade',cend:'endereco',cig:'instagram',cfb:'facebook',ctt:'tiktok',csi:'site',co:'obs'}[i]]||'');
  document.getElementById('cnas').value=c.nascimento||'';
  document.getElementById('cdc').value=c.desconto||0;
  document.getElementById('cfl').value=c.fiadoLimite||0;
  openM('m-cli');
}
function saveCliente(){
  const nome=vv('cn');if(!nome)return toast('⚠ Nome é obrigatório');
  const obj={id:S.editC||uid(),nome,empresa:vv('ce'),doc:vv('cd'),tel:vv('ct'),email:vv('cem'),
    cidade:vv('cc'),endereco:vv('cend'),nascimento:document.getElementById('cnas').value,
    instagram:vv('cig'),facebook:vv('cfb'),tiktok:vv('ctt'),site:vv('csi'),obs:vv('co'),
    desconto:+document.getElementById('cdc').value||0,fiadoLimite:+document.getElementById('cfl').value||0,
    criado:S.editC?(S.clientes.find(c=>c.id===S.editC)?.criado||Date.now()):Date.now()};
  S.editC?S.clientes=S.clientes.map(c=>c.id===S.editC?obj:c):S.clientes.push(obj);
  closeM('m-cli');saveDrive();toast(S.editC?'✓ Cliente atualizado':'✓ Cliente cadastrado!');renderPage();
}

// ══════════════════════════════════════════════════════
// MODAL ORÇAMENTO
// ══════════════════════════════════════════════════════
function popOrcModal(cid){
  document.getElementById('oc').innerHTML='<option value="">Sem cliente</option>'+S.clientes.map(c=>`<option value="${c.id}">${c.nome}</option>`).join('');
  if(cid)document.getElementById('oc').value=cid;
  document.getElementById('om').innerHTML=matOpts();
  document.getElementById('opr').innerHTML=prOpts();
}
function onCli(){
  const c=S.clientes.find(x=>x.id===document.getElementById('oc').value);
  if(c?.desconto)document.getElementById('odc').value=c.desconto;
  calcM();
}
function onPg(){
  document.getElementById('ent-row').style.display=document.getElementById('opg').value==='parcial'?'flex':'none';calcM();
}
function openOrc(cid){
  S.editO=null;document.getElementById('mo-t').textContent='Novo orçamento';
  popOrcModal(cid);
  const c=cid?S.clientes.find(x=>x.id===cid):null;
  ['on','oob'].forEach(i=>document.getElementById(i).value='');
  document.getElementById('ope').value=50;document.getElementById('ot').value=4;document.getElementById('oq').value=1;
  document.getElementById('olh').value=0.5;document.getElementById('olr').value=S.cfg.laborRate||40;
  document.getElementById('oex').value=0;document.getElementById('ofr').value=0;
  document.getElementById('omg').value=S.cfg.margem||40;document.getElementById('otx').value=S.cfg.imposto||6;
  document.getElementById('odc').value=c?.desconto||0;
  document.getElementById('ost').value='rascunho';document.getElementById('opg').value='pago';
  document.getElementById('oent').value=0;document.getElementById('ent-row').style.display='none';
  calcM();openM('m-orc');
}
function openOrcEdit(id){
  const o=S.orcamentos.find(x=>x.id===id);if(!o)return;
  S.editO=id;document.getElementById('mo-t').textContent='Editar orçamento';
  popOrcModal(o.clienteId);
  document.getElementById('on').value=o.nome||'';document.getElementById('om').value=o.matCusto||defMat().preco;
  document.getElementById('ope').value=o.peso||50;document.getElementById('ot').value=o.tempo||4;
  document.getElementById('oq').value=o.qty||1;document.getElementById('olh').value=o.laborH||0.5;
  document.getElementById('olr').value=o.laborR||40;document.getElementById('oex').value=o.extra||0;
  document.getElementById('ofr').value=o.frete||0;document.getElementById('omg').value=o.margem||40;
  document.getElementById('otx').value=o.tax||6;document.getElementById('odc').value=o.desconto||0;
  document.getElementById('ost').value=o.status||'rascunho';document.getElementById('opg').value=o.pagamento||'pago';
  document.getElementById('oob').value=o.obs||'';document.getElementById('oent').value=o.entrada||0;
  if(o.impressoraId)document.getElementById('opr').value=o.impressoraId;
  document.getElementById('ent-row').style.display=o.pagamento==='parcial'?'flex':'none';
  calcM();openM('m-orc');
}
function calcM(){
  const mat=gn('om')||defMat().preco,peso=gn('ope')||50,t=gn('ot')||4,qty=Math.max(1,gn('oq')||1);
  const lh=gn('olh'),lr=gn('olr')||40,ex=gn('oex'),fr=gn('ofr');
  const mg=(gn('omg')||40)/100,tx=(gn('otx')||6)/100,dc=(gn('odc')||0)/100;
  const pg=document.getElementById('opg')?.value||'pago';
  const ent=pg==='parcial'?gn('oent'):0;
  const pid=document.getElementById('opr')?.value;
  const pr=S.impressoras.find(x=>x.id===pid);
  const maqC=pr?pr.custoPorHora:S.cfg.maqCusto;const pot=pr?pr.potencia:S.cfg.maqPotencia;
  const bm=mat*peso,bmq=maqC*t,ben=(pot/1000)*t*S.cfg.energia,bl=lh*lr;
  const base=bm+bmq+ben+bl+ex+fr,pf=base*mg,pt=base+pf,taxes=pt*tx,preD=pt+taxes,disc=preD*dc,unit=preD-disc,total=unit*qty;
  const saldo=pg==='fiado'?total:pg==='parcial'?Math.max(0,total-ent):0;
  const el=document.getElementById('mcalc');if(!el)return{unit,total,saldo,disc,ent,mat,peso,t,qty,lh,lr,ex,fr,mg:mg*100,tx:tx*100,dc:dc*100,pg,pid};
  el.innerHTML=`<div class="crow"><span style="color:var(--mt)">Material</span><span>${R(bm)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Máquina${pr?' ('+pr.nome+')':''}</span><span>${R(bmq)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Energia</span><span>${R(ben)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Mão de obra</span><span>${R(bl)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Extras+frete</span><span>${R(ex+fr)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Lucro (${Math.round(mg*100)}%)</span><span>${R(pf)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Impostos (${Math.round(tx*100)}%)</span><span>${R(taxes)}</span></div>
    ${dc>0?`<div class="crow" style="color:var(--ok)"><span>Desconto (${Math.round(dc*100)}%)</span><span>−${R(disc)}</span></div>`:''}
    <div class="crow tot"><span>Total (${qty}x)</span><span>${R(total)}</span></div>
    ${saldo>0?`<div class="crow" style="color:var(--wn)"><span>Saldo devedor</span><span>${R(saldo)}</span></div>`:''}`;
  return{unit,total,saldo,disc,ent,mat,peso,t,qty,lh,lr,ex,fr,mg:mg*100,tx:tx*100,dc:dc*100,pg,pid};
}
function saveOrc(){
  const nome=vv('on');if(!nome)return toast('⚠ Nome da peça é obrigatório');
  const vals=calcM();const mc=gn('om');const pg=document.getElementById('opg').value;
  const obj={id:S.editO||uid(),nome,clienteId:document.getElementById('oc').value,
    matCusto:mc,material:matName(mc),impressoraId:document.getElementById('opr').value||null,
    peso:gn('ope'),tempo:gn('ot'),qty:gn('oq'),laborH:gn('olh'),laborR:gn('olr'),
    extra:gn('oex'),frete:gn('ofr'),margem:gn('omg'),tax:gn('otx'),desconto:gn('odc'),
    status:document.getElementById('ost').value,pagamento:pg,entrada:vals.ent,
    saldoDevedor:vals.saldo,obs:vv('oob'),total:vals.total,unitPrice:vals.unit,
    criado:S.editO?(S.orcamentos.find(o=>o.id===S.editO)?.criado||Date.now()):Date.now(),atualizado:Date.now()};
  S.editO?S.orcamentos=S.orcamentos.map(o=>o.id===S.editO?obj:o):S.orcamentos.push(obj);
  closeM('m-orc');saveDrive();toast(S.editO?'✓ Orçamento atualizado':'✓ Orçamento salvo!');
  setTimeout(()=>{if(confirm('Gerar PDF deste orçamento?'))gerarPDF(obj.id)},300);
  renderPage();
}

// ══════════════════════════════════════════════════════
// PDF
// ══════════════════════════════════════════════════════
function gerarPDF(orcId){
  if(!window.jspdf){toast('⚠ Aguarde o carregamento do jsPDF...');return}
  const o=S.orcamentos.find(x=>x.id===orcId);if(!o)return;
  const cl=S.clientes.find(c=>c.id===o.clienteId);
  const cfg=S.cfg;const PM=cfg.pdfMostrar||{};const PP=cfg.pdfPagamentos||{};
  const pr=S.impressoras.find(p=>p.id===o.impressoraId);
  const {jsPDF}=window.jspdf;
  const doc=new jsPDF({orientation:'portrait',unit:'mm',format:'a4'});
  const W=210,pad=16;let y=0;

  // ── HEADER AZUL
  doc.setFillColor(30,58,138);doc.rect(0,0,W,42,'F');
  // Logo
  if(cfg.logoBase64){try{doc.addImage(cfg.logoBase64,'PNG',pad,7,26,26)}catch(e){}}
  const lx=cfg.logoBase64?pad+30:pad;
  doc.setFontSize(18);doc.setFont('helvetica','bold');doc.setTextColor(255,255,255);
  doc.text(cfg.nomeLoja||'Print3D Manager',lx,18);
  // contato linha
  const cInfo=[];
  if(cfg.whatsapp)cInfo.push('📱 '+cfg.whatsapp);
  if(cfg.email)cInfo.push('✉ '+cfg.email);
  if(cfg.site)cInfo.push('🌐 '+cfg.site);
  if(cInfo.length){doc.setFontSize(8);doc.setFont('helvetica','normal');doc.setTextColor(180,210,255);doc.text(cInfo.join('   '),lx,25)}
  // redes sociais
  const rInfo=[];
  if(cfg.instagram)rInfo.push('📷 '+cfg.instagram);
  if(cfg.facebook)rInfo.push('📘 '+cfg.facebook);
  if(rInfo.length){doc.setFontSize(7);doc.setTextColor(160,195,255);doc.text(rInfo.join('   '),lx,30)}
  if(cfg.localizacao){doc.setFontSize(7);doc.setTextColor(160,195,255);doc.text('📍 '+cfg.localizacao,lx,35)}
  // ORÇAMENTO label
  doc.setFontSize(10);doc.setFont('helvetica','bold');doc.setTextColor(255,255,255);
  doc.text('ORÇAMENTO',W-pad,14,{align:'right'});
  doc.setFontSize(8);doc.setFont('helvetica','normal');doc.setTextColor(180,210,255);
  doc.text('#'+orcId.slice(-6).toUpperCase(),W-pad,20,{align:'right'});
  doc.text(dt(o.criado),W-pad,26,{align:'right'});
  y=48;

  // ── CLIENTE
  if(cl){
    doc.setFillColor(241,245,249);doc.rect(pad,y,W-pad*2,cl.empresa||cl.email?26:19,'F');
    doc.setFontSize(8);doc.setFont('helvetica','bold');doc.setTextColor(100,116,139);doc.text('PARA',pad+3,y+6);
    doc.setFontSize(11);doc.setFont('helvetica','bold');doc.setTextColor(15,23,42);doc.text(cl.nome,pad+3,y+13);
    if(cl.empresa){doc.setFontSize(8);doc.setFont('helvetica','normal');doc.setTextColor(100,116,139);doc.text(cl.empresa,pad+3,y+19)}
    const ctInfo=[cl.tel,cl.email].filter(Boolean).join('   ');
    if(ctInfo){doc.setFontSize(8);doc.setTextColor(100,116,139);doc.text(ctInfo,pad+3,y+(cl.empresa?24:19))}
    y+=(cl.empresa||cl.email?32:24);
  }

  // ── TÍTULO DA PEÇA
  doc.setFontSize(13);doc.setFont('helvetica','bold');doc.setTextColor(30,58,138);doc.text(o.nome,pad,y+7);
  doc.setFillColor(30,58,138);doc.rect(pad,y+9,W-pad*2,.5,'F');y+=15;

  // ── DETALHES (grid 2 colunas)
  const details=[];
  if(PM.material!==false)details.push(['Material',o.material]);
  if(PM.peso!==false)details.push(['Peso estimado',o.peso+'g']);
  if(PM.tempo!==false)details.push(['Tempo de impressão',o.tempo+'h']);
  if(PM.qty!==false)details.push(['Quantidade',o.qty+'x']);
  if(pr)details.push(['Impressora',pr.nome]);
  details.push(['Status',o.status.charAt(0).toUpperCase()+o.status.slice(1)]);
  if(o.desconto&&PM.desconto!==false)details.push(['Desconto aplicado',o.desconto+'%']);
  const cw2=(W-pad*2)/2;
  details.forEach((d,i)=>{
    const cx=pad+(i%2)*cw2,cy=y+Math.floor(i/2)*12;
    doc.setFontSize(7);doc.setFont('helvetica','normal');doc.setTextColor(100,116,139);doc.text(d[0].toUpperCase(),cx,cy);
    doc.setFontSize(10);doc.setFont('helvetica','bold');doc.setTextColor(15,23,42);doc.text(String(d[1]),cx,cy+5);
  });
  y+=Math.ceil(details.length/2)*12+6;

  // ── TABELA DE CUSTOS
  doc.setFillColor(241,245,249);doc.rect(pad,y,W-pad*2,7,'F');
  doc.setFontSize(8);doc.setFont('helvetica','bold');doc.setTextColor(100,116,139);
  doc.text('DESCRIÇÃO',pad+3,y+5);doc.text('VALOR',W-pad-3,y+5,{align:'right'});y+=9;
  const rows=[];
  if(PM.material!==false)rows.push(['Material ('+o.material+' · '+o.peso+'g)',R(o.matCusto*o.peso)]);
  rows.push(['Máquina'+(pr?' ('+pr.nome+')':''),R((pr?pr.custoPorHora:S.cfg.maqCusto)*o.tempo)]);
  rows.push(['Energia elétrica',R(((pr?pr.potencia:S.cfg.maqPotencia)/1000)*o.tempo*S.cfg.energia)]);
  if(PM.labor!==false)rows.push(['Mão de obra ('+o.laborH+'h × R$'+o.laborR+'/h)',R(o.laborH*o.laborR)]);
  if(PM.extras!==false&&o.extra)rows.push(['Acabamento / extras',R(o.extra)]);
  if(o.frete)rows.push(['Frete',R(o.frete)]);
  rows.forEach((row,i)=>{
    if(i%2===0){doc.setFillColor(250,251,252);doc.rect(pad,y-1,W-pad*2,7,'F')}
    doc.setFontSize(9);doc.setFont('helvetica','normal');doc.setTextColor(15,23,42);
    doc.text(row[0],pad+3,y+4);doc.text(row[1],W-pad-3,y+4,{align:'right'});y+=7;
  });
  doc.setFillColor(200,210,230);doc.rect(pad,y,W-pad*2,.5,'F');y+=4;
  if(PM.margem!==false){doc.setFontSize(8.5);doc.setFont('helvetica','normal');doc.setTextColor(100,116,139);doc.text('Margem de lucro ('+o.margem+'%)',pad+3,y+4);doc.text(R(o.unitPrice*(o.margem/100)/(1+(o.margem/100))),W-pad-3,y+4,{align:'right'});y+=7}
  if(PM.imposto!==false){doc.setFontSize(8.5);doc.setFont('helvetica','normal');doc.setTextColor(100,116,139);doc.text('Impostos ('+o.tax+'%)',pad+3,y+4);doc.text(R(o.total*(o.tax/100)),W-pad-3,y+4,{align:'right'});y+=7}
  if(o.desconto&&PM.desconto!==false){doc.setFontSize(8.5);doc.setFont('helvetica','bold');doc.setTextColor(22,101,52);doc.text('Desconto ('+o.desconto+'%)',pad+3,y+4);doc.text('−'+R(o.total*(o.desconto/100)/(1-(o.desconto/100))),W-pad-3,y+4,{align:'right'});y+=7;doc.setTextColor(15,23,42)}

  // TOTAL BOX
  y+=2;doc.setFillColor(30,58,138);doc.rect(pad,y,W-pad*2,11,'F');
  doc.setFontSize(11);doc.setFont('helvetica','bold');doc.setTextColor(255,255,255);
  doc.text('TOTAL',pad+4,y+7.5);doc.text(R(o.total),W-pad-4,y+7.5,{align:'right'});y+=15;
  if(PM.unitario!==false&&o.qty>1){doc.setFontSize(8);doc.setFont('helvetica','normal');doc.setTextColor(100,116,139);doc.text(o.qty+'x '+R(o.unitPrice)+' por peça',pad,y);y+=6}

  // PAGAMENTO STATUS
  if(o.pagamento==='fiado'){doc.setFillColor(255,247,237);doc.rect(pad,y,W-pad*2,9,'F');doc.setFontSize(9);doc.setFont('helvetica','bold');doc.setTextColor(154,52,18);doc.text('⚠ Pagamento a prazo — Saldo em aberto: '+R(o.saldoDevedor||o.total),pad+3,y+6);y+=13}
  else if(o.pagamento==='parcial'){doc.setFillColor(255,247,237);doc.rect(pad,y,W-pad*2,9,'F');doc.setFontSize(9);doc.setFont('helvetica','bold');doc.setTextColor(154,52,18);doc.text('Entrada: '+R(o.entrada||0)+'   Saldo restante: '+R(o.saldoDevedor||0),pad+3,y+6);y+=13}

  // ── PAGAMENTOS ACEITOS
  const pgList=[];
  if(PP.pix!==false&&cfg.pix)pgList.push('Pix: '+cfg.pix);
  if(PP.cartao!==false)pgList.push('Cartão débito/crédito');
  if(PP.dinheiro!==false)pgList.push('Dinheiro');
  if(PP.link!==false&&cfg.linkPagamento)pgList.push('Link: '+cfg.linkPagamento);
  if(pgList.length){
    y+=2;doc.setFontSize(8);doc.setFont('helvetica','bold');doc.setTextColor(30,58,138);doc.text('FORMAS DE PAGAMENTO ACEITAS',pad,y);y+=5;
    pgList.forEach(p=>{doc.setFontSize(8.5);doc.setFont('helvetica','normal');doc.setTextColor(15,23,42);doc.text('• '+p,pad+2,y);y+=5});
  }

  // ── QR CODE (se tiver)
  if(PP.qrcode!==false&&cfg.qrcodeBase64){
    try{
      doc.setFontSize(8);doc.setFont('helvetica','bold');doc.setTextColor(30,58,138);
      y+=3;doc.text('QR CODE PIX',W-pad-30,y);
      doc.addImage(cfg.qrcodeBase64,'PNG',W-pad-30,y+2,28,28);
    }catch(e){}
  }

  // ── OBS
  if(o.obs){y+=4;doc.setFontSize(8);doc.setFont('helvetica','bold');doc.setTextColor(100,116,139);doc.text('OBSERVAÇÕES',pad,y);y+=5;
    doc.setFont('helvetica','normal');doc.setTextColor(15,23,42);
    const obsL=doc.splitTextToSize(o.obs,W-pad*2);doc.text(obsL,pad,y);y+=obsL.length*4+4}

  // ── FOOTER
  const footY=285;
  doc.setFillColor(241,245,249);doc.rect(0,footY-2,W,14,'F');
  doc.setFontSize(8);doc.setFont('helvetica','italic');doc.setTextColor(100,116,139);
  doc.text(cfg.assinatura||'Obrigado pela preferência!',W/2,footY+3,{align:'center'});
  const footLinks=[];
  if(cfg.site)footLinks.push('🌐 '+cfg.site);
  if(cfg.instagram)footLinks.push('📷 '+cfg.instagram);
  if(cfg.localizacao)footLinks.push('📍 '+cfg.localizacao);
  if(footLinks.length){doc.setFontSize(7);doc.setFont('helvetica','normal');doc.text(footLinks.join('   '),W/2,footY+8,{align:'center'})}
  doc.setFontSize(7);doc.setTextColor(180,190,200);doc.text('Gerado em '+new Date().toLocaleString('pt-BR'),W/2,footY+12,{align:'center'});

  S._pdf=doc;S._pdfOrcId=orcId;
  const blob=doc.output('blob');
  const url=URL.createObjectURL(blob);
  document.getElementById('pdf-fr').src=url;
  openM('m-pdf');
}
function dlPDF(){
  if(!S._pdf)return;
  const o=S.orcamentos.find(x=>x.id===S._pdfOrcId);
  S._pdf.save(`orcamento_${(o?.nome||'orc').replace(/\s+/g,'_')}_${(S._pdfOrcId||'').slice(-4)}.pdf`);
  toast('✓ PDF baixado!');
}
function wppSend(){
  if(!S._pdf||!S._pdfOrcId)return;
  const o=S.orcamentos.find(x=>x.id===S._pdfOrcId);
  const cl=S.clientes.find(c=>c.id===o?.clienteId);
  const pix=S.cfg.pix?`\n💳 Pix: *${S.cfg.pix}*`:'';
  const link=S.cfg.linkPagamento?`\n🔗 ${S.cfg.linkPagamento}`:'';
  const msg=`Olá${cl?', '+cl.nome.split(' ')[0]:''}! 😊\n\n📦 *${o.nome}*\n• Material: ${o.material} · ${o.peso}g · ${o.qty}x\n${o.desconto?'• Desconto: '+o.desconto+'%\n':''}\n💰 Por peça: ${R(o.unitPrice)}\n📋 *Total: ${R(o.total)}*\n${o.pagamento==='fiado'?'💳 A prazo\n':''}\n${S.cfg.assinatura||'Qualquer dúvida, estou à disposição!'}${pix}${link}\n\n${S.cfg.nomeLoja||''}${S.cfg.whatsapp?' · '+S.cfg.whatsapp:''}`;
  dlPDF();
  const tel=cl?.tel?.replace(/\D/g,'');
  setTimeout(()=>window.open(tel?`https://wa.me/55${tel}?text=${encodeURIComponent(msg)}`:`https://wa.me/?text=${encodeURIComponent(msg)}`,'_blank'),600);
}

// ══════════════════════════════════════════════════════
// CALCULADORA
// ══════════════════════════════════════════════════════
function rCalc(){
  return`<div style="max-width:640px">
  <div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:18px;margin-bottom:13px">
    <div style="font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.5px;color:var(--mt);margin-bottom:13px">Material e impressora</div>
    <div class="g3">
      <div class="fg"><label>Impressora</label><select id="s-pr" oninput="calcSC()">${prOpts()}</select></div>
      <div class="fg"><label>Material</label><select id="sm" oninput="calcSC()">${matOpts()}</select></div>
      <div class="fg"><label>Peso (g)</label><input id="sp" type="number" value="50" oninput="calcSC()"></div>
      <div class="fg"><label>Tempo (h)</label><input id="st" type="number" value="4" step="0.5" oninput="calcSC()"></div>
      <div class="fg"><label>Custo máquina (R$/h)</label><input id="smq" type="number" value="${S.cfg.maqCusto}" step="0.5" oninput="calcSC()"></div>
      <div class="fg"><label>Energia (R$/kWh)</label><input id="skw" type="number" value="${S.cfg.energia}" step="0.1" oninput="calcSC()"></div>
    </div>
  </div>
  <div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:18px;margin-bottom:13px">
    <div style="font-size:11px;font-weight:600;text-transform:uppercase;letter-spacing:.5px;color:var(--mt);margin-bottom:13px">Custos adicionais</div>
    <div class="g3">
      <div class="fg"><label>Mão de obra (h)</label><input id="slh" type="number" value="0.5" step="0.25" oninput="calcSC()"></div>
      <div class="fg"><label>Taxa/hora (R$)</label><input id="slr" type="number" value="${S.cfg.laborRate}" step="5" oninput="calcSC()"></div>
      <div class="fg"><label>Acabamento (R$)</label><input id="sfn" type="number" value="0" oninput="calcSC()"></div>
      <div class="fg"><label>Frete (R$)</label><input id="sfr" type="number" value="0" oninput="calcSC()"></div>
      <div class="fg"><label>Falhas (%)</label><input id="sfl" type="number" value="${S.cfg.falha}" step="1" oninput="calcSC()"></div>
      <div class="fg"><label>Desconto (%)</label><input id="sdc" type="number" value="0" step="5" oninput="calcSC()"></div>
    </div>
  </div>
  <div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:18px;margin-bottom:13px">
    <div class="g3">
      <div class="fg"><label>Margem (%)</label><input id="smg" type="number" value="${S.cfg.margem}" step="5" oninput="calcSC()"></div>
      <div class="fg"><label>Impostos (%)</label><input id="stx" type="number" value="${S.cfg.imposto}" step="1" oninput="calcSC()"></div>
      <div class="fg"><label>Quantidade</label><input id="sqt" type="number" value="1" min="1" oninput="calcSC()"></div>
    </div>
  </div>
  <div style="background:var(--sur);border:1px solid var(--bdr);border-radius:var(--r);padding:18px">
    <div id="scr"></div>
    <button class="btn pr" style="width:100%;margin-top:13px" onclick="scToOrc()">Salvar como orçamento →</button>
  </div></div>`;
}
function calcSC(){
  const pid=document.getElementById('s-pr')?.value;
  const pr=S.impressoras.find(x=>x.id===pid);
  const mat=gn('sm')||defMat().preco,peso=gn('sp')||50,t=gn('st')||4;
  const maq=pr?pr.custoPorHora:(gn('smq')||S.cfg.maqCusto),pw=pr?pr.potencia:S.cfg.maqPotencia;
  const kw=gn('skw')||S.cfg.energia,lh=gn('slh'),lr=gn('slr')||S.cfg.laborRate;
  const fn=gn('sfn'),fr=gn('sfr'),fl=gn('sfl')/100;
  const mg=(gn('smg')||S.cfg.margem)/100,tx=(gn('stx')||S.cfg.imposto)/100,dc=gn('sdc')/100,qty=Math.max(1,gn('sqt')||1);
  const bm=mat*peso,bmq=maq*t,ben=(pw/1000)*t*kw,bl=lh*lr;
  const base=bm+bmq+ben+bl+fn+fr,bfl=base*fl,wf=base+bfl,pf=wf*mg,prt=wf+pf,taxes=prt*tx,preD=prt+taxes,disc=preD*dc,unit=preD-disc,total=unit*qty;
  S._sc={mat,peso,t,mg:mg*100,tx:tx*100,qty,unit,total,lh,lr,fn,fr,fl:fl*100,dc:dc*100,pid};
  const el=document.getElementById('scr');if(!el)return;
  el.innerHTML=`<div style="display:grid;grid-template-columns:1fr 1fr 1fr;gap:11px;margin-bottom:13px">
    <div class="scard"><div class="sl">Custo base</div><div class="sv" style="font-size:15px">${R(wf)}</div></div>
    <div class="scard"><div class="sl">Por unidade</div><div class="sv" style="font-size:15px">${R(unit)}</div></div>
    <div class="scard" style="border-color:var(--ac);background:var(--acb)"><div class="sl">Total</div><div class="sv" style="font-size:15px;color:var(--ac)">${R(total)}</div></div>
  </div><div class="csec">
    <div class="crow"><span style="color:var(--mt)">Material</span><span>${R(bm)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Máquina${pr?' ('+pr.nome+')':''}</span><span>${R(bmq)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Energia</span><span>${R(ben)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Mão de obra</span><span>${R(bl)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Extras+frete</span><span>${R(fn+fr)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Contingência</span><span>${R(bfl)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Lucro (${Math.round(mg*100)}%)</span><span>${R(pf)}</span></div>
    <div class="crow"><span style="color:var(--mt)">Impostos (${Math.round(tx*100)}%)</span><span>${R(taxes)}</span></div>
    ${dc>0?`<div class="crow" style="color:var(--ok)"><span>Desconto (${Math.round(dc*100)}%)</span><span>−${R(disc)}</span></div>`:''}
    <div class="crow tot"><span>Total por peça</span><span>${R(unit)}</span></div>
  </div>`;
}
function scToOrc(){
  nav('orc');setTimeout(()=>{openOrc();if(S._sc){
    document.getElementById('om').value=S._sc.mat;document.getElementById('ope').value=S._sc.peso;
    document.getElementById('ot').value=S._sc.t;document.getElementById('oq').value=S._sc.qty;
    document.getElementById('omg').value=S._sc.mg;document.getElementById('otx').value=S._sc.tx;
    document.getElementById('olh').value=S._sc.lh;document.getElementById('olr').value=S._sc.lr;
    document.getElementById('oex').value=S._sc.fn;document.getElementById('ofr').value=S._sc.fr;
    document.getElementById('odc').value=S._sc.dc;
    if(S._sc.pid)document.getElementById('opr').value=S._sc.pid;calcM();}},120);
}

// ══════════════════════════════════════════════════════
// CONFIGURAÇÕES
// ══════════════════════════════════════════════════════
function rCfg(){
  const PM=S.cfg.pdfMostrar||{};const PP=S.cfg.pdfPagamentos||{};
  const chk=(key,lbl,obj)=>`<label class="chk-row"><input type="checkbox" ${obj[key]!==false?'checked':''} onchange="S.cfg.${obj===PM?'pdfMostrar':'pdfPagamentos'}['${key}']=this.checked"> ${lbl}</label>`;
  return`<div style="max-width:780px">

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Impressoras</h3><p>Cadastre suas impressoras com custos individuais</p></div><button class="btn pr" onclick="openImp()">+ Nova impressora</button></div>
  <div style="padding:0 18px">${S.impressoras.length?S.impressoras.map(p=>`<div class="lr">
    <div style="flex:1;min-width:0">
      <div style="display:flex;align-items:center;gap:7px"><span style="font-weight:500;font-size:13px">${p.nome}</span>${badge('gy',p.tipo||'FDM')}${p.padrao?badge('bl','padrão'):''}</div>
      <div style="font-size:11px;color:var(--mt);margin-top:2px">${[p.volume?'Vol: '+p.volume:null,p.obs].filter(Boolean).join(' · ')}</div>
    </div>
    <div style="font-family:'DM Mono',monospace;font-size:12px;color:var(--mt);min-width:130px;text-align:right">${R(p.custoPorHora)}/h · ${p.potencia}W</div>
    <div style="display:flex;gap:4px;margin-left:9px">
      ${!p.padrao?`<button class="btn sm" onclick="setImpPad('${p.id}')">☆</button>`:`<button class="btn sm" style="color:var(--ac)" disabled>★</button>`}
      <button class="btn sm" onclick="openImp('${p.id}')">Editar</button>
      <button class="btn sm dg" onclick="delImp('${p.id}')">✕</button>
    </div></div>`).join(''):`<div class="empty" style="padding:25px 0"><p>Nenhuma impressora cadastrada</p></div>`}</div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Materiais</h3><p>Gerencie materiais e custos por grama</p></div><button class="btn pr" onclick="openMat()">+ Novo material</button></div>
  <div style="padding:0 18px">${S.materiais.map(m=>`<div class="lr">
    <div style="flex:1;min-width:0">
      <div style="display:flex;align-items:center;gap:6px"><span style="font-weight:500;font-size:13px">${m.nome}</span>${m.padrao?badge('bl','padrão'):''}</div>
      ${m.desc?`<div style="font-size:11px;color:var(--mt);margin-top:2px">${m.desc}</div>`:''}
    </div>
    <div style="font-family:'DM Mono',monospace;font-size:13px;color:var(--ac);min-width:90px;text-align:right">R$ ${m.preco.toFixed(2)}/g</div>
    <div style="display:flex;gap:4px;margin-left:9px">
      ${!m.padrao?`<button class="btn sm" onclick="setMatPad('${m.id}')">☆</button>`:`<button class="btn sm" style="color:var(--ac)" disabled>★</button>`}
      <button class="btn sm" onclick="openMat('${m.id}')">Editar</button>
      <button class="btn sm dg" onclick="delMat('${m.id}')">✕</button>
    </div></div>`).join('')}</div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Padrões globais de custo</h3><p>Usados quando não há impressora específica selecionada</p></div></div>
  <div class="cb"><div class="g3">
    <div class="fg"><label>Custo máquina padrão (R$/h)</label><input id="cfg-maq" type="number" step="0.5" value="${S.cfg.maqCusto}"></div>
    <div class="fg"><label>Potência padrão (W)</label><input id="cfg-pw" type="number" step="10" value="${S.cfg.maqPotencia}"></div>
    <div class="fg"><label>Energia (R$/kWh)</label><input id="cfg-kw" type="number" step="0.1" value="${S.cfg.energia}"></div>
    <div class="fg"><label>Taxa mão de obra (R$/h)</label><input id="cfg-lab" type="number" step="5" value="${S.cfg.laborRate}"></div>
    <div class="fg"><label>Margem padrão (%)</label><input id="cfg-mg" type="number" step="5" value="${S.cfg.margem}"></div>
    <div class="fg"><label>Impostos padrão (%)</label><input id="cfg-tx" type="number" step="1" value="${S.cfg.imposto}"></div>
    <div class="fg"><label>Taxa de falhas (%)</label><input id="cfg-fl" type="number" step="1" value="${S.cfg.falha}"></div>
  </div><div style="display:flex;justify-content:flex-end;margin-top:14px;padding-top:13px;border-top:1px solid var(--bdr)">
    <button class="btn pr" onclick="saveCfgGlobal()">Salvar padrões</button>
  </div></div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Dados do negócio</h3><p>Aparece no PDF e mensagens do WhatsApp</p></div></div>
  <div class="cb"><div class="g2">
    <div class="fg"><label>Nome do negócio / marca</label><input id="cfg-loja" value="${S.cfg.nomeLoja||''}" placeholder="Print3D Campina Grande"></div>
    <div class="fg"><label>WhatsApp / Telefone</label><input id="cfg-wpp" value="${S.cfg.whatsapp||''}" placeholder="(83) 99999-9999"></div>
    <div class="fg"><label>E-mail</label><input id="cfg-email" value="${S.cfg.email||''}" placeholder="contato@print3d.com.br"></div>
    <div class="fg"><label>Site</label><input id="cfg-site" value="${S.cfg.site||''}" placeholder="https://print3d.com.br"></div>
    <div class="fg"><label>Instagram</label><input id="cfg-ig" value="${S.cfg.instagram||''}" placeholder="@print3d_cg"></div>
    <div class="fg"><label>Facebook</label><input id="cfg-fb" value="${S.cfg.facebook||''}" placeholder="facebook.com/print3d"></div>
    <div class="fg s2"><label>Localização / Endereço</label><input id="cfg-loc" value="${S.cfg.localizacao||''}" placeholder="Rua da Impressão, 3D — Campina Grande / PB"></div>
    <div class="fg s2"><label>Assinatura do orçamento</label><input id="cfg-ass" value="${S.cfg.assinatura||''}" placeholder="Qualquer dúvida, estou à disposição! 😊"></div>
  </div>
  <div style="display:flex;justify-content:flex-end;margin-top:14px;padding-top:13px;border-top:1px solid var(--bdr)">
    <button class="btn pr" onclick="saveCfgNeg()">Salvar dados</button>
  </div></div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Pagamentos no PDF</h3><p>Configure as formas de pagamento e dados exibidos no orçamento</p></div></div>
  <div class="cb"><div class="g2">
    <div class="fg"><label>Chave Pix</label><input id="cfg-pix" value="${S.cfg.pix||''}" placeholder="CPF, e-mail, telefone, chave aleatória"></div>
    <div class="fg"><label>Tipo da chave Pix</label>
      <select id="cfg-pixtp"><option ${S.cfg.pixTipo==='chave'?'selected':''}>chave</option><option ${S.cfg.pixTipo==='cpf'?'selected':''}>cpf</option><option ${S.cfg.pixTipo==='email'?'selected':''}>email</option><option ${S.cfg.pixTipo==='telefone'?'selected':''}>telefone</option></select>
    </div>
    <div class="fg s2"><label>Link de pagamento (Mercado Pago, PagSeguro, etc.)</label><input id="cfg-link" value="${S.cfg.linkPagamento||''}" placeholder="https://mpago.la/..."></div>
    <div class="fg"><label>Logo (PNG/JPG — aparece no PDF)</label>
      <input type="file" id="cfg-logo" accept="image/*" onchange="loadImg(this,'logo')" style="padding:5px">
      ${S.cfg.logoBase64?`<div style="margin-top:6px;display:flex;align-items:center;gap:8px"><img src="${S.cfg.logoBase64}" style="height:36px;border-radius:4px;border:1px solid var(--bdr)"><button class="btn sm dg" onclick="S.cfg.logoBase64='';toast('Logo removida');nav('cfg')">Remover</button></div>`:''}
    </div>
    <div class="fg"><label>QR Code Pix (imagem PNG — aparece no PDF)</label>
      <input type="file" id="cfg-qr" accept="image/*" onchange="loadImg(this,'qrcode')" style="padding:5px">
      ${S.cfg.qrcodeBase64?`<div style="margin-top:6px;display:flex;align-items:center;gap:8px"><img src="${S.cfg.qrcodeBase64}" style="height:50px;border-radius:4px;border:1px solid var(--bdr)"><button class="btn sm dg" onclick="S.cfg.qrcodeBase64='';toast('QR removido');nav('cfg')">Remover</button></div>`:''}
    </div>
  </div>
  <div class="sdiv">Formas de pagamento a exibir no PDF</div>
  <div style="display:flex;gap:0;flex-wrap:wrap">
    ${chk('pix','Pix',PP)}${chk('cartao','Cartão débito/crédito',PP)}${chk('dinheiro','Dinheiro',PP)}${chk('link','Link de pagamento',PP)}${chk('qrcode','QR Code Pix',PP)}
  </div>
  <div style="display:flex;justify-content:flex-end;margin-top:14px;padding-top:13px;border-top:1px solid var(--bdr)">
    <button class="btn pr" onclick="saveCfgPag()">Salvar pagamentos</button>
  </div></div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Itens visíveis no PDF</h3><p>Escolha o que o cliente verá no orçamento gerado</p></div></div>
  <div class="cb">
    <div style="display:grid;grid-template-columns:1fr 1fr;gap:4px">
      ${chk('material','Mostrar material e peso',PM)}${chk('peso','Mostrar peso separado',PM)}
      ${chk('tempo','Mostrar tempo de impressão',PM)}${chk('qty','Mostrar quantidade',PM)}
      ${chk('labor','Mostrar mão de obra',PM)}${chk('extras','Mostrar acabamento/extras',PM)}
      ${chk('margem','Mostrar margem de lucro',PM)}${chk('imposto','Mostrar impostos',PM)}
      ${chk('desconto','Mostrar desconto',PM)}${chk('subtotal','Mostrar subtotais',PM)}
      ${chk('unitario','Mostrar preço unitário',PM)}
    </div>
    <div style="display:flex;justify-content:flex-end;margin-top:14px;padding-top:13px;border-top:1px solid var(--bdr)">
      <button class="btn pr" onclick="saveDrive();toast('✓ Configurações do PDF salvas!')">Salvar preferências</button>
    </div>
  </div></div>

  <div class="cs"><div class="ch"><div class="ch-t"><h3>Google Drive</h3><p>Sincronização automática dos dados</p></div></div>
  <div class="cb" style="display:flex;align-items:center;gap:13px">
    <div class="dr-dot ${S.driveOk?'ok':''}" style="width:10px;height:10px;flex-shrink:0"></div>
    <div style="flex:1"><div style="font-size:13px;font-weight:500">${S.driveOk?'Conectado ao Google Drive':'Não conectado'}</div>
    <div style="font-size:12px;color:var(--mt)">${S.driveOk?'Salvo em print3d_dados.json no seu Drive':'Dados apenas locais'}</div></div>
    <button class="btn ${S.driveOk?'':'pr'}" onclick="connectDrive()">${S.driveOk?'Reconectar':'Conectar Drive'}</button>
    ${S.driveOk?`<button class="btn" onclick="saveDrive().then(()=>toast('✓ Sincronizado!'))">↻ Sincronizar</button>`:''}
  </div></div>
  </div>`;
}

function saveCfgGlobal(){
  S.cfg.maqCusto=gn('cfg-maq')||3.5;S.cfg.maqPotencia=gn('cfg-pw')||150;
  S.cfg.energia=gn('cfg-kw')||0.9;S.cfg.laborRate=gn('cfg-lab')||40;
  S.cfg.margem=gn('cfg-mg')||40;S.cfg.imposto=gn('cfg-tx')||6;S.cfg.falha=gn('cfg-fl')||5;
  saveDrive();toast('✓ Padrões salvos!');
}
function saveCfgNeg(){
  S.cfg.nomeLoja=vv('cfg-loja');S.cfg.whatsapp=vv('cfg-wpp');S.cfg.email=vv('cfg-email');
  S.cfg.site=vv('cfg-site');S.cfg.instagram=vv('cfg-ig');S.cfg.facebook=vv('cfg-fb');
  S.cfg.localizacao=vv('cfg-loc');S.cfg.assinatura=vv('cfg-ass');
  saveDrive();toast('✓ Dados do negócio salvos!');
}
function saveCfgPag(){
  S.cfg.pix=vv('cfg-pix');S.cfg.pixTipo=document.getElementById('cfg-pixtp')?.value||'chave';
  S.cfg.linkPagamento=vv('cfg-link');
  saveDrive();toast('✓ Dados de pagamento salvos!');
}
function loadImg(input,key){
  const file=input.files[0];if(!file)return;
  if(file.size>600000)return toast('⚠ Imagem muito grande. Use menos de 600KB.');
  const r=new FileReader();r.onload=e=>{
    if(key==='logo')S.cfg.logoBase64=e.target.result;
    else S.cfg.qrcodeBase64=e.target.result;
    saveDrive();nav('cfg');toast('✓ Imagem carregada!');
  };r.readAsDataURL(file);
}

// ── IMPRESSORAS
function openImp(id){
  S.editImp=id||null;document.getElementById('mi-t').textContent=id?'Editar impressora':'Nova impressora';
  const p=id?S.impressoras.find(x=>x.id===id):{};
  document.getElementById('in').value=p.nome||'';document.getElementById('ih').value=p.custoPorHora||3.5;
  document.getElementById('ipw').value=p.potencia||150;document.getElementById('ivol').value=p.volume||'';
  document.getElementById('itp').value=p.tipo||'FDM';document.getElementById('iob').value=p.obs||'';
  document.getElementById('ipad').checked=p.padrao||false;openM('m-imp');
}
function saveImp(){
  const nome=vv('in');if(!nome)return toast('⚠ Nome é obrigatório');
  const isPad=document.getElementById('ipad').checked;
  if(isPad)S.impressoras.forEach(p=>p.padrao=false);
  const obj={id:S.editImp||uid(),nome,custoPorHora:gn('ih')||3.5,potencia:gn('ipw')||150,
    volume:vv('ivol'),tipo:document.getElementById('itp').value,obs:vv('iob'),padrao:isPad};
  S.editImp?S.impressoras=S.impressoras.map(p=>p.id===S.editImp?obj:p):S.impressoras.push(obj);
  closeM('m-imp');saveDrive();toast(S.editImp?'✓ Impressora atualizada':'✓ Impressora adicionada!');nav('cfg');
}
function delImp(id){S.impressoras=S.impressoras.filter(x=>x.id!==id);saveDrive();toast('✓ Removida');nav('cfg')}
function setImpPad(id){S.impressoras.forEach(p=>p.padrao=p.id===id);saveDrive();toast('✓ Padrão atualizado');nav('cfg')}

// ── MATERIAIS
function openMat(id){
  S.editMat=id||null;document.getElementById('mm-t').textContent=id?'Editar material':'Novo material';
  const m=id?S.materiais.find(x=>x.id===id):{};
  document.getElementById('mn').value=m.nome||'';document.getElementById('mp').value=m.preco||'';
  document.getElementById('md').value=m.desc||'';document.getElementById('mdef').checked=m.padrao||false;openM('m-mat');
}
function saveMat(){
  const nome=vv('mn'),preco=parseFloat(document.getElementById('mp').value);
  if(!nome)return toast('⚠ Nome é obrigatório');if(!preco||preco<=0)return toast('⚠ Custo inválido');
  const isPad=document.getElementById('mdef').checked;if(isPad)S.materiais.forEach(m=>m.padrao=false);
  const obj={id:S.editMat||uid(),nome,preco,desc:vv('md'),padrao:isPad};
  S.editMat?S.materiais=S.materiais.map(m=>m.id===S.editMat?obj:m):S.materiais.push(obj);
  closeM('m-mat');saveDrive();toast(S.editMat?'✓ Material atualizado':'✓ Material adicionado!');nav('cfg');
}
function delMat(id){
  if(S.materiais.length<=1)return toast('⚠ Mantenha ao menos um material');
  const m=S.materiais.find(x=>x.id===id);if(m?.padrao){const o=S.materiais.find(x=>x.id!==id);if(o)o.padrao=true}
  S.materiais=S.materiais.filter(x=>x.id!==id);saveDrive();toast('✓ Material removido');nav('cfg');
}
function setMatPad(id){S.materiais.forEach(m=>m.padrao=m.id===id);saveDrive();toast('✓ Padrão atualizado');nav('cfg')}

// ── UTILS
function confDel(tipo,id){
  const msgs={cli:'Excluir este cliente? Os orçamentos não serão excluídos.',orc:'Excluir este orçamento permanentemente?',lanc:'Excluir este lançamento?'};
  document.getElementById('dl-t').textContent='Confirmar exclusão';
  document.getElementById('dl-m').textContent=msgs[tipo]||'Confirmar?';
  document.getElementById('dl-ok').onclick=()=>{
    if(tipo==='cli')S.clientes=S.clientes.filter(c=>c.id!==id);
    else if(tipo==='orc')S.orcamentos=S.orcamentos.filter(o=>o.id!==id);
    else if(tipo==='lanc')S.lancamentos=S.lancamentos.filter(l=>l.id!==id);
    closeM('m-del');saveDrive();toast('✓ Excluído');renderPage();
  };openM('m-del');
}

// ── INIT
loadLocal();initDrive();renderPage();
</script>
</body>
</html>
