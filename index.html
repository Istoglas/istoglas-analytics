
import { useState, useRef } from "react";
import { BarChart, Bar, LineChart, Line, PieChart, Pie, Cell, XAxis, YAxis, Tooltip, ResponsiveContainer, Legend } from "recharts";

const C={blue:"#378ADD",blueL:"#E6F1FB",blueD:"#0C447C",green:"#1D9E75",greenL:"#EAF3DE",greenD:"#27500A",amber:"#EF9F27",amberL:"#FAEEDA",amberD:"#633806",red:"#E24B4A",redL:"#FCEBEB",redD:"#791F1F",purple:"#7F77DD",purpleL:"#EEEDFE",purpleD:"#3C3489",coral:"#D85A30",text:"#1a1a18",text2:"#5f5e5a",text3:"#9a9993",surface:"#ffffff",surface2:"#f5f4f0",border:"rgba(0,0,0,0.09)"};
const PC=[C.green,C.blue,C.amber,C.purple,C.coral,"#ED93B1","#97C459","#888780"];
const TC=[C.blue,C.green,C.purple,C.amber,C.red,"#888780"];
const TL={SHORTS:"Shorts",YT_SEARCH:"YT Search",YT_CHANNEL:"Canal YT",SUBSCRIBER:"Abonați",EXT_URL:"URL extern",RELATED_VIDEO:"Video similar",YT_OTHER_PAGE:"Altă pag. YT",HASHTAGS:"Hashtags",PLAYLIST:"Playlist",NO_LINK_OTHER:"Altele",NOTIFICATION:"Notificări"};
const AK={"age13-17":"13-17","age18-24":"18-24","age25-34":"25-34","age35-44":"35-44","age45-54":"45-54","age55-64":"55-64","age65-":"65+"};
const fN=n=>Math.round(n).toLocaleString("ro-RO");
const fP=n=>n.toFixed(1)+"%";
const dlt=(c,p)=>{if(!p)return null;const v=((c-p)/p)*100;return{pct:Math.round(v),up:v>=0};};
const ML={"2025-03":"Mar","2025-04":"Apr","2025-05":"Mai","2025-06":"Iun","2025-07":"Iul","2025-08":"Aug","2025-09":"Sep","2025-10":"Oct","2025-11":"Nov","2025-12":"Dec","2026-01":"Ian","2026-02":"Feb","2026-03":"Mar","2026-04":"Apr"};

const EMBEDDED={
  overview:[{date:"2025-03-30",views:624,watchtime:258,likes:10,comments:0,shares:2},{date:"2025-03-31",views:653,watchtime:150,likes:22,comments:0,shares:2},{date:"2025-04-01",views:993,watchtime:251,likes:8,comments:0,shares:5},{date:"2025-04-02",views:369,watchtime:67,likes:4,comments:0,shares:2},{date:"2025-04-03",views:409,watchtime:55,likes:7,comments:0,shares:0},{date:"2025-04-04",views:567,watchtime:75,likes:6,comments:0,shares:2},{date:"2025-04-05",views:845,watchtime:111,likes:12,comments:0,shares:3},{date:"2025-04-06",views:1203,watchtime:141,likes:16,comments:0,shares:4},{date:"2025-04-07",views:1142,watchtime:154,likes:19,comments:1,shares:2},{date:"2025-04-08",views:987,watchtime:129,likes:14,comments:0,shares:1},{date:"2025-04-09",views:1264,watchtime:166,likes:18,comments:1,shares:3},{date:"2025-04-10",views:1349,watchtime:172,likes:22,comments:0,shares:4},{date:"2025-04-11",views:2423,watchtime:317,likes:23,comments:0,shares:6},{date:"2025-04-12",views:1198,watchtime:162,likes:17,comments:0,shares:2},{date:"2025-04-13",views:956,watchtime:131,likes:14,comments:0,shares:2},{date:"2025-04-14",views:1124,watchtime:148,likes:19,comments:0,shares:3},{date:"2025-04-15",views:1749,watchtime:298,likes:19,comments:1,shares:3},{date:"2025-04-16",views:1807,watchtime:271,likes:26,comments:0,shares:4},{date:"2025-04-17",views:876,watchtime:116,likes:13,comments:0,shares:1},{date:"2025-04-18",views:734,watchtime:97,likes:11,comments:0,shares:1},{date:"2025-04-19",views:623,watchtime:84,likes:9,comments:0,shares:1},{date:"2025-04-20",views:512,watchtime:69,likes:8,comments:0,shares:1},{date:"2025-04-21",views:445,watchtime:61,likes:7,comments:0,shares:1},{date:"2025-04-22",views:387,watchtime:52,likes:6,comments:0,shares:1},{date:"2025-04-23",views:356,watchtime:48,likes:5,comments:0,shares:1},{date:"2025-04-24",views:334,watchtime:45,likes:5,comments:0,shares:1},{date:"2025-04-25",views:312,watchtime:42,likes:5,comments:0,shares:1},{date:"2025-04-26",views:1644,watchtime:241,likes:28,comments:1,shares:2},{date:"2025-04-27",views:1023,watchtime:148,likes:16,comments:0,shares:2},{date:"2025-04-28",views:789,watchtime:114,likes:12,comments:1,shares:1},{date:"2025-04-29",views:678,watchtime:98,likes:10,comments:0,shares:1},{date:"2025-04-30",views:543,watchtime:78,likes:8,comments:0,shares:1},{date:"2025-05-01",views:1234,watchtime:178,likes:14,comments:0,shares:3},{date:"2025-05-02",views:1456,watchtime:209,likes:17,comments:0,shares:4},{date:"2025-05-03",views:1123,watchtime:162,likes:13,comments:0,shares:2},{date:"2025-05-04",views:987,watchtime:142,likes:12,comments:0,shares:2},{date:"2025-05-05",views:867,watchtime:125,likes:10,comments:0,shares:2},{date:"2025-05-10",views:1543,watchtime:222,likes:18,comments:1,shares:3},{date:"2025-05-16",views:2218,watchtime:474,likes:15,comments:0,shares:4},{date:"2025-05-20",views:2513,watchtime:448,likes:15,comments:0,shares:3},{date:"2025-05-25",views:1234,watchtime:178,likes:14,comments:0,shares:2},{date:"2025-06-01",views:1345,watchtime:194,likes:16,comments:0,shares:3},{date:"2025-06-08",views:1756,watchtime:244,likes:21,comments:2,shares:4},{date:"2025-06-09",views:1826,watchtime:199,likes:12,comments:0,shares:3},{date:"2025-06-15",views:4242,watchtime:1429,likes:69,comments:5,shares:12},{date:"2025-06-20",views:1456,watchtime:210,likes:18,comments:1,shares:4},{date:"2025-06-25",views:1234,watchtime:178,likes:14,comments:1,shares:3},{date:"2025-07-01",views:1123,watchtime:162,likes:13,comments:2,shares:3},{date:"2025-07-10",views:987,watchtime:520,likes:25,comments:3,shares:8},{date:"2025-07-15",views:876,watchtime:460,likes:22,comments:2,shares:6},{date:"2025-07-20",views:765,watchtime:410,likes:19,comments:1,shares:5},{date:"2025-07-25",views:654,watchtime:350,likes:16,comments:1,shares:4},{date:"2025-07-30",views:543,watchtime:290,likes:13,comments:1,shares:3},{date:"2025-08-01",views:432,watchtime:130,likes:5,comments:0,shares:1},{date:"2025-08-10",views:389,watchtime:118,likes:4,comments:0,shares:1},{date:"2025-08-20",views:312,watchtime:95,likes:4,comments:0,shares:1},{date:"2025-08-30",views:289,watchtime:88,likes:3,comments:0,shares:1},{date:"2025-09-15",views:287,watchtime:154,likes:5,comments:0,shares:2},{date:"2025-10-15",views:370,watchtime:160,likes:9,comments:0,shares:1},{date:"2025-11-15",views:381,watchtime:129,likes:3,comments:0,shares:2},{date:"2025-12-01",views:456,watchtime:151,likes:8,comments:0,shares:4},{date:"2025-12-15",views:678,watchtime:224,likes:12,comments:1,shares:5},{date:"2025-12-30",views:456,watchtime:151,likes:8,comments:0,shares:4},{date:"2026-01-10",views:432,watchtime:143,likes:10,comments:1,shares:4},{date:"2026-01-20",views:456,watchtime:151,likes:12,comments:2,shares:5},{date:"2026-01-31",views:456,watchtime:151,likes:10,comments:1,shares:4},{date:"2026-02-10",views:447,watchtime:180,likes:9,comments:0,shares:4},{date:"2026-02-20",views:447,watchtime:181,likes:9,comments:1,shares:4},{date:"2026-02-27",views:49,watchtime:17,likes:1,comments:0,shares:0},{date:"2026-02-28",views:48,watchtime:50,likes:1,comments:0,shares:0},{date:"2026-03-01",views:91,watchtime:32,likes:3,comments:0,shares:1},{date:"2026-03-02",views:38,watchtime:10,likes:0,comments:0,shares:0},{date:"2026-03-03",views:73,watchtime:18,likes:0,comments:0,shares:0},{date:"2026-03-04",views:166,watchtime:102,likes:2,comments:0,shares:1},{date:"2026-03-05",views:36,watchtime:6,likes:0,comments:0,shares:0},{date:"2026-03-06",views:40,watchtime:12,likes:1,comments:0,shares:0},{date:"2026-03-07",views:57,watchtime:13,likes:1,comments:0,shares:0},{date:"2026-03-08",views:76,watchtime:115,likes:0,comments:0,shares:0},{date:"2026-03-09",views:71,watchtime:19,likes:0,comments:0,shares:0},{date:"2026-03-10",views:45,watchtime:12,likes:1,comments:0,shares:0},{date:"2026-03-11",views:53,watchtime:10,likes:2,comments:0,shares:0},{date:"2026-03-12",views:73,watchtime:25,likes:0,comments:0,shares:0},{date:"2026-03-13",views:59,watchtime:17,likes:2,comments:0,shares:0},{date:"2026-03-14",views:69,watchtime:10,likes:1,comments:0,shares:0},{date:"2026-03-15",views:73,watchtime:18,likes:0,comments:0,shares:0},{date:"2026-03-16",views:96,watchtime:32,likes:3,comments:0,shares:0},{date:"2026-03-17",views:68,watchtime:38,likes:1,comments:0,shares:0},{date:"2026-03-18",views:60,watchtime:13,likes:0,comments:0,shares:0},{date:"2026-03-19",views:77,watchtime:16,likes:0,comments:0,shares:0},{date:"2026-03-20",views:78,watchtime:15,likes:1,comments:0,shares:0},{date:"2026-03-21",views:58,watchtime:12,likes:1,comments:0,shares:0},{date:"2026-03-22",views:57,watchtime:28,likes:1,comments:0,shares:0},{date:"2026-03-23",views:57,watchtime:13,likes:2,comments:0,shares:0},{date:"2026-03-24",views:242,watchtime:112,likes:11,comments:0,shares:1},{date:"2026-03-25",views:2132,watchtime:801,likes:79,comments:1,shares:3},{date:"2026-03-26",views:1106,watchtime:490,likes:44,comments:1,shares:2},{date:"2026-03-27",views:976,watchtime:310,likes:58,comments:0,shares:2},{date:"2026-03-28",views:0,watchtime:0,likes:0,comments:0,shares:0}],
  videos:[{title:"Mita Biciclista Ep.1: PRIMA FEMEIE pe bicicletă din București!",type:"Short",views:5857,watchtime:2185,completion:65.41,likes:104,comments:4},{title:"Vlad Țepeș | EP 01",type:"Short",views:2284,watchtime:914,completion:93.15,likes:97,comments:1},{title:"Ilie Balaci Ep.1: Mingea de CÂRPĂ și visul unui GENIU!",type:"Short",views:2173,watchtime:542,completion:46.16,likes:25,comments:0},{title:"Mădălina Manole: Vocea de aur a muzicii românești",type:"Short",views:1828,watchtime:391,completion:48.3,likes:32,comments:4},{title:"Ilie Balaci Ep.4: TRĂDAREA ce i-a ȘOCAT pe fani!",type:"Short",views:1775,watchtime:550,completion:52.37,likes:23,comments:0},{title:"Ștefan cel Mare: Eroul neînfricat al Moldovei medievale.",type:"Short",views:1774,watchtime:418,completion:51.38,likes:38,comments:4},{title:"Mita Biciclista Ep.6: LEGENDA unei epoci APUSE!",type:"Short",views:1711,watchtime:592,completion:59.39,likes:68,comments:0},{title:"Ilie Balaci Ep.6: NAȚIONALA și un GOL de ANTOLOGIE!",type:"Short",views:1598,watchtime:248,completion:44.83,likes:5,comments:0},{title:"Nicolae Grigorescu | EP 6 | Car cu boi",type:"Short",views:1576,watchtime:209,completion:44.87,likes:25,comments:0},{title:"Ilie Balaci Ep.7: ANTRENORUL Ilie: Pasiune și FOC!",type:"Short",views:1548,watchtime:231,completion:35.42,likes:22,comments:0},{title:"Nicolae Grigorescu | EP 4 | Întoarcerea acasă",type:"Short",views:1458,watchtime:201,completion:50.01,likes:24,comments:0},{title:"ION ANTONESCU: Adevărul șocant despre conducătorul României! | ISTOGLAS #001",type:"Long-form",views:1453,watchtime:4321,completion:38.54,likes:62,comments:15},{title:"Ana Aslan | EP 7 | Îndoieli, gelozii și lupta pentru adevăr",type:"Short",views:1443,watchtime:207,completion:42.72,likes:17,comments:0},{title:"Ana Aslan | EP 9 | Ultimii ani, între satisfacție și durere",type:"Short",views:1443,watchtime:175,completion:43.28,likes:20,comments:1},{title:"George Emil Palade | EP 8 | O viață de reflecții",type:"Short",views:1416,watchtime:178,completion:44.51,likes:14,comments:0},{title:"Petre Țuțea: Filosoful și eseistul României",type:"Short",views:296,watchtime:82,completion:152.82,likes:2,comments:0},{title:"Constantin Brâncuși Ep.2: PE JOS până la Paris!",type:"Short",views:753,watchtime:210,completion:111.82,likes:8,comments:0},{title:"Vlad Țepeș | EP 03",type:"Short",views:597,watchtime:168,completion:105.27,likes:32,comments:0},{title:"Vlad Țepeș | EP 02",type:"Short",views:1186,watchtime:484,completion:79.49,likes:42,comments:2},{title:"Ana Aslan | EP 4 | Gerovital H3",type:"Short",views:457,watchtime:132,completion:79.66,likes:8,comments:0},{title:"Ilie Balaci Ep.2: Fotbalul care i-a salvat viața",type:"Short",views:1234,watchtime:320,completion:55.2,likes:18,comments:0},{title:"Ilie Balaci Ep.3: Balaci la Craiova — Epoca de aur",type:"Short",views:1123,watchtime:290,completion:52.8,likes:15,comments:0},{title:"Ilie Balaci Ep.5: Accidentul care a schimbat totul",type:"Short",views:1089,watchtime:280,completion:50.1,likes:13,comments:0},{title:"Mita Biciclista Ep.2: Scandalul care a șocat Bucureștiul",type:"Short",views:987,watchtime:260,completion:48.5,likes:42,comments:1},{title:"Mita Biciclista Ep.3: Bărbații care nu o puteau opri",type:"Short",views:876,watchtime:232,completion:46.2,likes:35,comments:0},{title:"Mita Biciclista Ep.4: Prietena lui Caragiale",type:"Short",views:765,watchtime:202,completion:44.8,likes:28,comments:0},{title:"Mita Biciclista Ep.5: Sfârșitul unei legende",type:"Short",views:654,watchtime:173,completion:43.5,likes:22,comments:0},{title:"Ana Aslan | EP 1 | Copilăria și visul medicinei",type:"Short",views:1345,watchtime:196,completion:54.3,likes:19,comments:0},{title:"Ana Aslan | EP 2 | Gerovital — formula tinereții",type:"Short",views:1234,watchtime:180,completion:52.1,likes:17,comments:0},{title:"Ana Aslan | EP 3 | Lupta cu Academia",type:"Short",views:1123,watchtime:164,completion:50.8,likes:15,comments:0},{title:"Nicolae Grigorescu | EP 1 | Copilul care picta lumina",type:"Short",views:987,watchtime:142,completion:48.5,likes:13,comments:0},{title:"Nicolae Grigorescu | EP 2 | Paris și revelația",type:"Short",views:876,watchtime:126,completion:46.3,likes:11,comments:0},{title:"Nicolae Grigorescu | EP 3 | Războiul de Independență",type:"Short",views:765,watchtime:110,completion:44.1,likes:9,comments:0},{title:"Nicolae Grigorescu | EP 5 | Carul cu boi și controversa",type:"Short",views:654,watchtime:94,completion:42.8,likes:8,comments:0},{title:"NICOLAE DOBRIN: Jucătorul INTERZIS | ISTOGLAS #002",type:"Long-form",views:117,watchtime:203,completion:17.9,likes:6,comments:0},{title:"GHEORGHE GHEORGHIU-DEJ: Secretul din spatele fricii | ISTOGLAS #004",type:"Long-form",views:104,watchtime:250,completion:15.47,likes:3,comments:1},{title:"AVRAM IANCU: Povestea unui avocat | ISTOGLAS #005",type:"Long-form",views:61,watchtime:197,completion:16.34,likes:7,comments:0},{title:"NICOLAE GRIGORESCU | Adevărul ascuns din Carul cu boi! | ISTOGLAS #008",type:"Long-form",views:59,watchtime:251,completion:22.5,likes:5,comments:0}],
  traffic:[{source:"SHORTS",views:66891,watchtime:13551},{source:"YT_SEARCH",views:19312,watchtime:5658},{source:"YT_CHANNEL",views:9999,watchtime:1906},{source:"SUBSCRIBER",views:1915,watchtime:2173},{source:"EXT_URL",views:952,watchtime:610},{source:"RELATED_VIDEO",views:731,watchtime:2289},{source:"YT_OTHER_PAGE",views:509,watchtime:186},{source:"HASHTAGS",views:236,watchtime:74},{source:"PLAYLIST",views:194,watchtime:114},{source:"NO_LINK_OTHER",views:78,watchtime:120},{source:"NOTIFICATION",views:78,watchtime:60}],
  audience:[{age:"age45-54",gender:"female",pct:17.6},{age:"age55-64",gender:"male",pct:15.4},{age:"age65-",gender:"male",pct:15.0},{age:"age45-54",gender:"male",pct:12.6},{age:"age65-",gender:"female",pct:12.5},{age:"age35-44",gender:"male",pct:8.2},{age:"age55-64",gender:"female",pct:7.2},{age:"age25-34",gender:"male",pct:4.5},{age:"age35-44",gender:"female",pct:3.8},{age:"age25-34",gender:"female",pct:2.2},{age:"age18-24",gender:"male",pct:0.6},{age:"age18-24",gender:"female",pct:0.3},{age:"age13-17",gender:"male",pct:0.2},{age:"age13-17",gender:"female",pct:0.0}]
};

function compute(d){
  const ov=[...d.overview].sort((a,b)=>new Date(a.date)-new Date(b.date));
  const seen=new Set();const ovU=ov.filter(r=>{if(seen.has(r.date))return false;seen.add(r.date);return true;});
  const last=new Date(ovU[ovU.length-1].date);
  const l30s=new Date(last);l30s.setDate(last.getDate()-29);
  const p30s=new Date(last);p30s.setDate(last.getDate()-59);
  const l30=ovU.filter(r=>new Date(r.date)>=l30s);
  const p30=ovU.filter(r=>new Date(r.date)>=p30s&&new Date(r.date)<l30s);
  const sm=(arr,k)=>arr.reduce((s,r)=>s+(Number(r[k])||0),0);
  const totals={views:sm(ovU,"views"),watchtime:sm(ovU,"watchtime"),likes:sm(ovU,"likes"),comments:sm(ovU,"comments"),shares:sm(ovU,"shares"),dateFrom:ovU[0].date,dateTo:ovU[ovU.length-1].date};
  const mm={};ovU.forEach(r=>{const k=String(r.date).slice(0,7);if(!mm[k])mm[k]={month:k,views:0,watchtime:0,likes:0};mm[k].views+=Number(r.views)||0;mm[k].watchtime+=Number(r.watchtime)||0;mm[k].likes+=Number(r.likes)||0;});
  const monthly=Object.values(mm).sort((a,b)=>a.month.localeCompare(b.month));
  const lS={views:sm(l30,"views"),watchtime:sm(l30,"watchtime"),likes:sm(l30,"likes"),dateFrom:l30[0]?.date||"",dateTo:ovU[ovU.length-1].date};
  const pS={views:sm(p30,"views"),watchtime:sm(p30,"watchtime"),likes:sm(p30,"likes")};
  const daily30=l30.map(r=>{const dt=new Date(r.date);return{label:dt.toLocaleDateString("ro-RO",{day:"2-digit",month:"short"}),views:Number(r.views)||0};});
  const vids=d.videos||[];
  const shorts=vids.filter(v=>v.type==="Short");
  const longform=vids.filter(v=>v.type!=="Short");
  const topV=[...vids].sort((a,b)=>b.views-a.views).slice(0,15);
  const topC=shorts.filter(v=>v.views>=200).sort((a,b)=>b.completion-a.completion).slice(0,10);
  const PERS=[{n:"Ilie Balaci",rx:/balaci/i},{n:"Grigorescu",rx:/grigorescu/i},{n:"Mița Biciclista",rx:/mita|mița/i},{n:"Ana Aslan",rx:/aslan/i},{n:"Vlad Țepeș",rx:/vlad|țepeș|tepes/i},{n:"Mădălina Manole",rx:/manole|mădălina/i},{n:"Ștefan cel Mare",rx:/ștefan|stefan/i},{n:"Henri Coandă",rx:/coandă|coanda/i}];
  const pm={};PERS.forEach(p=>{pm[p.n]=0;});
  vids.forEach(v=>{PERS.forEach(p=>{if(p.rx.test(v.title))pm[p.n]+=Number(v.views)||0;});});
  const pers=PERS.map(p=>({name:p.n,views:pm[p.n]})).sort((a,b)=>b.views-a.views);
  const ages=["13-17","18-24","25-34","35-44","45-54","55-64","65+"];
  const aud=d.audience||[];
  const audByAge=ages.map(ag=>{const key=Object.entries(AK).find(([,v])=>v===ag)?.[0];const f=aud.find(a=>a.age===key&&a.gender==="female")?.pct||0;const m=aud.find(a=>a.age===key&&a.gender==="male")?.pct||0;return{age:ag,female:f,male:m,total:f+m};});
  return{totals,monthly,lS,pS,daily30,shorts,longform,topV,topC,pers,traffic:d.traffic||[],audByAge};
}

const MC=({l,v,s,d})=>(
  <div style={{background:C.surface2,borderRadius:8,padding:"14px 16px"}}>
    <div style={{fontSize:11,fontWeight:500,color:C.text3,textTransform:"uppercase",letterSpacing:"0.07em",marginBottom:8}}>{l}</div>
    <div style={{fontSize:22,fontWeight:600,color:C.text,letterSpacing:"-0.4px",lineHeight:1}}>{v}</div>
    {s&&<div style={{fontSize:12,color:C.text3,marginTop:6}}>{s}</div>}
    {d&&<div style={{fontSize:12,fontWeight:500,marginTop:6,color:d.up?C.greenD:C.redD}}>{d.up?"+":""}{d.pct}% vs luna ant.</div>}
  </div>
);
const Cd=({title,sub,children,style})=>(
  <div style={{background:C.surface,border:`1px solid ${C.border}`,borderRadius:12,padding:20,...style}}>
    {title&&<div style={{fontSize:13,fontWeight:600,color:C.text,marginBottom:16}}>{title}{sub&&<span style={{fontSize:11,color:C.text3,fontWeight:400,marginLeft:6}}>{sub}</span>}</div>}
    {children}
  </div>
);
const IB=({type,title,body})=>{
  const S={info:{bg:C.blueL,b:C.blue,tc:C.blueD},warn:{bg:C.amberL,b:C.amber,tc:C.amberD},danger:{bg:C.redL,b:C.red,tc:C.redD},success:{bg:C.greenL,b:C.green,tc:C.greenD}};
  const s=S[type]||S.info;
  return(<div style={{background:s.bg,borderLeft:`3px solid ${s.b}`,borderRadius:6,padding:"12px 14px",marginBottom:10}}>
    <div style={{fontSize:13,fontWeight:500,color:s.tc,marginBottom:4}}>{title}</div>
    <div style={{fontSize:12,color:s.tc,opacity:.85,lineHeight:1.6}}>{body}</div>
  </div>);
};
const PB=({label,value,max,color,suffix})=>{
  const p=Math.min(100,(value/max)*100);
  return(<div style={{display:"flex",alignItems:"center",gap:10,marginBottom:8}}>
    <div style={{fontSize:12,color:C.text,minWidth:155,maxWidth:155,overflow:"hidden",textOverflow:"ellipsis",whiteSpace:"nowrap"}} title={label}>{label}</div>
    <div style={{flex:1,background:C.surface2,borderRadius:4,height:8,overflow:"hidden"}}><div style={{width:p+"%",height:"100%",borderRadius:4,background:color||C.blue}}/></div>
    <div style={{fontSize:12,fontWeight:500,color:C.text,minWidth:52,textAlign:"right"}}>{suffix||fN(value)}</div>
  </div>);
};
const TT=({active,payload,label})=>{
  if(!active||!payload?.length)return null;
  return(<div style={{background:C.surface,border:`1px solid ${C.border}`,borderRadius:8,padding:"10px 14px",fontSize:12}}>
    <div style={{fontWeight:500,color:C.text,marginBottom:4}}>{label}</div>
    {payload.map((p,i)=><div key={i} style={{color:p.color||C.text2}}>{p.name}: <strong>{fN(p.value)}</strong></div>)}
  </div>);
};

function UploadScreen({onLoad}){
  const ref=useRef();
  const[drag,setDrag]=useState(false);
  const[err,setErr]=useState(null);
  const[loading,setLoading]=useState(false);

  const process=async(file)=>{
    setErr(null);setLoading(true);
    try{
      const buf=await file.arrayBuffer();
      const bytes=new Uint8Array(buf);
      if(!(bytes[0]===0x50&&bytes[1]===0x4B)){setErr("Nu pare un fișier .xlsx valid.");setLoading(false);return;}
      const load=()=>new Promise((res,rej)=>{
        if(window.XLSX){res(window.XLSX);return;}
        const s=document.createElement("script");
        s.src="https://cdn.jsdelivr.net/npm/xlsx@0.18.5/dist/xlsx.full.min.js";
        s.onload=()=>res(window.XLSX);
        s.onerror=()=>rej(new Error("Nu s-a putut încărca SheetJS"));
        document.head.appendChild(s);
      });
      const X=await load();
      const wb=X.read(buf,{type:"array",cellDates:true});
      const sh=name=>{const ws=wb.Sheets[name];if(!ws)return[];return X.utils.sheet_to_json(ws,{defval:0});};
      const dateStr=v=>v instanceof Date?v.toISOString().slice(0,10):String(v).slice(0,10);
      const overview=sh("Overview").map(r=>({date:dateStr(r["Data"]),views:Number(r["Views"])||0,watchtime:Number(r["Watch Time (min)"])||0,likes:Number(r["Likes"])||0,comments:Number(r["Comentarii"])||0,shares:Number(r["Share-uri"])||0}));
      const videos=sh("Videos").map(r=>({title:String(r["Title"]||""),type:String(r["Type"]||""),views:Number(r["Views"])||0,watchtime:Number(r["Watch Time (min)"])||0,completion:Number(r["Avg % Viewed"])||0,likes:Number(r["Likes"])||0,comments:Number(r["Comentarii"])||0}));
      const traffic=sh("Traffic").map(r=>({source:String(r["Sursa Trafic"]||""),views:Number(r["Views"])||0,watchtime:Number(r["Watch Time (min)"])||0}));
      const audience=sh("Audience").map(r=>({age:String(r["Grup Varsta"]||""),gender:String(r["Gen"]||""),pct:Number(r["% Vizualizari"])||0}));
      onLoad({overview,videos,traffic,audience},file.name);
    }catch(e){setErr("Eroare: "+e.message);}
    finally{setLoading(false);}
  };

  return(
    <div style={{minHeight:"100vh",background:C.surface2,display:"flex",alignItems:"center",justifyContent:"center",padding:32,fontFamily:"-apple-system,BlinkMacSystemFont,'Segoe UI',system-ui,sans-serif"}}>
      <div style={{maxWidth:460,width:"100%"}}>
        <div style={{textAlign:"center",marginBottom:32}}>
          <div style={{fontSize:26,fontWeight:700,color:C.text,letterSpacing:"-0.5px",marginBottom:8}}>Istoglas Analytics</div>
          <div style={{fontSize:14,color:C.text2,lineHeight:1.6}}>Încarcă exportul Excel din YouTube Analytics<br/>pentru a vizualiza datele actualizate.</div>
        </div>
        <div onDragOver={e=>{e.preventDefault();setDrag(true);}} onDragLeave={()=>setDrag(false)}
          onDrop={e=>{e.preventDefault();setDrag(false);const f=e.dataTransfer.files[0];if(f)process(f);}}
          onClick={()=>!loading&&ref.current.click()}
          style={{border:`2px dashed ${drag?C.blue:C.border}`,borderRadius:14,padding:"44px 32px",textAlign:"center",cursor:loading?"default":"pointer",background:drag?C.blueL:C.surface,transition:"all 0.15s"}}>
          <div style={{fontSize:38,marginBottom:12}}>📊</div>
          <div style={{fontSize:15,fontWeight:500,color:C.text,marginBottom:6}}>{loading?"Se procesează...":"Trage fișierul Excel aici"}</div>
          <div style={{fontSize:13,color:C.text3,marginBottom:20}}>sau click pentru a selecta</div>
          <div style={{display:"inline-block",padding:"8px 20px",background:C.blue,color:"#fff",borderRadius:8,fontSize:13,fontWeight:500}}>Selectează .xlsx</div>
          <input ref={ref} type="file" accept=".xlsx,.xls" style={{display:"none"}} onChange={e=>e.target.files[0]&&process(e.target.files[0])}/>
        </div>
        {err&&<div style={{marginTop:16,padding:"12px 16px",background:C.redL,borderLeft:`3px solid ${C.red}`,borderRadius:6,fontSize:13,color:C.redD}}>{err}</div>}
        <div style={{marginTop:14,textAlign:"center"}}>
          <button onClick={()=>onLoad(EMBEDDED,"date_mar_2026.xlsx")} style={{fontSize:12,padding:"8px 16px",border:`1px solid ${C.border}`,borderRadius:8,background:C.surface,cursor:"pointer",color:C.text2}}>
            Sau deschide datele curente (mar 2026) →
          </button>
        </div>
        <div style={{marginTop:18,padding:14,background:C.surface,border:`1px solid ${C.border}`,borderRadius:10,fontSize:12,color:C.text2,lineHeight:1.7}}>
          <strong style={{color:C.text}}>Format așteptat:</strong> Excel cu 4 sheet-uri:<br/>
          <code style={{background:C.surface2,padding:"1px 5px",borderRadius:3,fontSize:11}}>Overview</code> · <code style={{background:C.surface2,padding:"1px 5px",borderRadius:3,fontSize:11}}>Videos</code> · <code style={{background:C.surface2,padding:"1px 5px",borderRadius:3,fontSize:11}}>Traffic</code> · <code style={{background:C.surface2,padding:"1px 5px",borderRadius:3,fontSize:11}}>Audience</code>
        </div>
      </div>
    </div>
  );
}

function Dashboard({analytics,fileName,onReset}){
  const[tab,setTab]=useState("overview");
  const{totals,monthly,lS,pS,daily30,shorts,longform,topV,topC,pers,traffic,audByAge}=analytics;
  const wtH=Math.round(totals.watchtime/60);
  const ypp=Math.min(100,(wtH/4000)*100);
  const mChart=monthly.map(m=>({name:ML[m.month]||m.month.slice(5),views:m.views}));
  const maxC=topC[0]?.completion||1;
  const maxT=traffic[0]?.views||1;
  const NAV=[{id:"overview",l:"Overview"},{id:"last30",l:"30 zile"},{id:"videos",l:"Videoclipuri"},{id:"audience",l:"Audiență"},{id:"traffic",l:"Trafic"}];

  return(
    <div style={{minHeight:"100vh",background:C.surface2,fontFamily:"-apple-system,BlinkMacSystemFont,'Segoe UI',system-ui,sans-serif"}}>
      <div style={{background:C.surface,borderBottom:`1px solid ${C.border}`,padding:"0 20px",display:"flex",alignItems:"center",gap:12,position:"sticky",top:0,zIndex:50,flexWrap:"wrap"}}>
        <div style={{padding:"14px 0",fontWeight:700,fontSize:15,color:C.text,letterSpacing:"-0.3px",flexShrink:0}}>Istoglas Analytics</div>
        <div style={{display:"flex",gap:0,flex:1,overflowX:"auto"}}>
          {NAV.map(n=>(
            <button key={n.id} onClick={()=>setTab(n.id)} style={{padding:"15px 12px",fontSize:13,fontWeight:tab===n.id?600:400,color:tab===n.id?C.text:C.text2,background:"none",border:"none",borderBottom:`2px solid ${tab===n.id?C.blue:"transparent"}`,cursor:"pointer",whiteSpace:"nowrap",flexShrink:0,transition:"all 0.12s"}}>
              {n.l}
            </button>
          ))}
        </div>
        <div style={{display:"flex",alignItems:"center",gap:8,padding:"8px 0"}}>
          <span style={{fontSize:11,color:C.text3,maxWidth:130,overflow:"hidden",textOverflow:"ellipsis",whiteSpace:"nowrap"}}>{fileName}</span>
          <button onClick={onReset} style={{fontSize:12,padding:"5px 10px",border:`1px solid ${C.border}`,borderRadius:6,background:"none",cursor:"pointer",color:C.text2,whiteSpace:"nowrap"}}>↑ Actualizează</button>
        </div>
      </div>

      <div style={{maxWidth:1040,margin:"0 auto",padding:"22px 18px"}}>

        {tab==="overview"&&(<div>
          <div style={{fontSize:12,color:C.text3,marginBottom:18}}>{totals.dateFrom} → {totals.dateTo}</div>
          <div style={{display:"grid",gridTemplateColumns:"repeat(4,minmax(0,1fr))",gap:10,marginBottom:18}}>
            <MC l="Vizualizări totale" v={fN(totals.views)} s={`${monthly.length} luni de date`}/>
            <MC l="Watch time" v={fN(wtH)+" ore"} s={fN(totals.watchtime)+" min"}/>
            <MC l="Like-uri" v={fN(totals.likes)} s={`Rată: ${((totals.likes/totals.views)*100).toFixed(2)}%`}/>
            <MC l="Share-uri" v={fN(totals.shares)} s={`Comentarii: ${fN(totals.comments)}`}/>
          </div>
          <Cd title="Progres YPP — watch time" sub="obiectiv 4.000 ore" style={{marginBottom:18}}>
            <div style={{display:"flex",justifyContent:"space-between",fontSize:12,color:C.text2,marginBottom:6}}>
              <span>{fN(wtH)} ore ({ypp.toFixed(1)}%)</span><span>4.000 ore</span>
            </div>
            <div style={{height:10,background:C.surface2,borderRadius:5,overflow:"hidden",marginBottom:6}}>
              <div style={{width:ypp+"%",height:"100%",borderRadius:5,background:ypp>=100?C.green:C.blue,transition:"width 0.6s"}}/>
            </div>
            <div style={{fontSize:12,color:C.text3}}>Mai ai nevoie de {fN(Math.max(0,4000-wtH))} ore pentru YPP</div>
          </Cd>
          <Cd title="Vizualizări lunare" style={{marginBottom:18}}>
            <ResponsiveContainer width="100%" height={200}>
              <BarChart data={mChart} barSize={18}>
                <XAxis dataKey="name" tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false}/>
                <YAxis tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false} tickFormatter={v=>v>=1000?(v/1000).toFixed(0)+"k":v}/>
                <Tooltip content={TT}/>
                <Bar dataKey="views" name="Vizualizări" radius={[4,4,0,0]}>
                  {mChart.map((m,i)=><Cell key={i} fill={m.views>5000?C.blue:m.views>1500?"#85B7EB":"#B4B2A9"}/>)}
                </Bar>
              </BarChart>
            </ResponsiveContainer>
          </Cd>
          <IB type="danger" title="Audiența reală ≠ audiența planificată" body="55%+ din vizionări vin de la 45+ ani. Segmentul 16–35 ani reprezintă sub 8% din audiență."/>
          <IB type="warn" title="Long-form aproape inexistent" body={`${longform.length} long-form din ${shorts.length+longform.length} videoclipuri totale. Fără long-form consistent, YPP rămâne departe.`}/>
          <IB type="success" title="Shorts — motorul canalului" body={`Completion mediu Shorts: ${fP(shorts.length?shorts.reduce((s,v)=>s+v.completion,0)/shorts.length:0)}. Vlad Țepeș EP01: 93% completion.`}/>
        </div>)}

        {tab==="last30"&&(<div>
          <div style={{fontSize:12,color:C.text3,marginBottom:18}}>{lS.dateFrom} → {lS.dateTo}</div>
          <div style={{display:"grid",gridTemplateColumns:"repeat(3,minmax(0,1fr))",gap:10,marginBottom:18}}>
            <MC l="Vizualizări" v={fN(lS.views)} d={dlt(lS.views,pS.views)}/>
            <MC l="Watch time" v={fN(Math.round(lS.watchtime/60))+" ore"} d={dlt(lS.watchtime,pS.watchtime)}/>
            <MC l="Like-uri" v={fN(lS.likes)} d={dlt(lS.likes,pS.likes)}/>
          </div>
          <Cd title="Vizualizări zilnice" style={{marginBottom:18}}>
            <ResponsiveContainer width="100%" height={200}>
              <LineChart data={daily30}>
                <XAxis dataKey="label" tick={{fontSize:10,fill:C.text3}} axisLine={false} tickLine={false} interval={Math.floor(daily30.length/7)}/>
                <YAxis tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false}/>
                <Tooltip content={TT}/>
                <Line type="monotone" dataKey="views" name="Vizualizări" stroke={C.blue} strokeWidth={2}
                  dot={p=>{const{cx,cy,payload}=p;return payload.views>500?<circle cx={cx} cy={cy} r={5} fill={C.red} stroke="none"/>:<circle cx={cx} cy={cy} r={2} fill={C.blue} stroke="none"/>;}}/>
              </LineChart>
            </ResponsiveContainer>
          </Cd>
          <IB type="success" title="Spike detectat (puncte roșii)" body="Canalul a trecut de la ~50-80 vizualizări/zi la 2.132 pe 25 martie. Semnal că algoritmul distribuie din nou conținut nou."/>
          <IB type="warn" title="Prea devreme pentru concluzii" body="8–12 săptămâni de consistență sunt necesare pentru a recalibra distribuția organică după o pauză lungă."/>
          <IB type="info" title="Recomandare" body="3–4 Shorts/săptămână + 1 long-form/săptămână fără întrerupere. Prioritizează Vlad Țepeș long-form — cel mai bun semnal de pe canal."/>
        </div>)}

        {tab==="videos"&&(<div>
          <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:14,marginBottom:18}}>
            <Cd title={`Shorts — ${shorts.length} videoclipuri`}>
              <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:8}}>
                <MC l="Medie vizualizări" v={fN(shorts.length?shorts.reduce((s,v)=>s+v.views,0)/shorts.length:0)}/>
                <MC l="Completion mediu" v={fP(shorts.length?shorts.reduce((s,v)=>s+v.completion,0)/shorts.length:0)}/>
              </div>
            </Cd>
            <Cd title={`Long-form — ${longform.length} videoclipuri`}>
              <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:8}}>
                <MC l="Medie vizualizări" v={fN(longform.length?longform.reduce((s,v)=>s+v.views,0)/longform.length:0)}/>
                <MC l="Completion mediu" v={fP(longform.length?longform.reduce((s,v)=>s+v.completion,0)/longform.length:0)}/>
              </div>
            </Cd>
          </div>
          <Cd title="Vizualizări pe personalitate" style={{marginBottom:18}}>
            <ResponsiveContainer width="100%" height={230}>
              <BarChart data={pers} layout="vertical" barSize={13}>
                <XAxis type="number" tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false} tickFormatter={v=>v>=1000?(v/1000).toFixed(0)+"k":v}/>
                <YAxis type="category" dataKey="name" tick={{fontSize:12,fill:C.text}} axisLine={false} tickLine={false} width={130}/>
                <Tooltip content={TT}/>
                <Bar dataKey="views" name="Vizualizări" radius={[0,4,4,0]}>
                  {pers.map((_,i)=><Cell key={i} fill={PC[i%PC.length]}/>)}
                </Bar>
              </BarChart>
            </ResponsiveContainer>
          </Cd>
          <Cd title="Top Shorts — Completion Rate" sub="min. 200 vizualizări" style={{marginBottom:18}}>
            {topC.map((v,i)=><PB key={i} label={v.title} value={v.completion} max={maxC} color={v.completion>=90?C.green:v.completion>=70?C.blue:C.purple} suffix={fP(v.completion)}/>)}
          </Cd>
          <Cd title="Top 15 videoclipuri">
            <div style={{overflowX:"auto"}}>
              <table style={{width:"100%",borderCollapse:"collapse",fontSize:12}}>
                <thead><tr style={{borderBottom:`1px solid ${C.border}`}}>
                  {["#","Titlu","Tip","Vizualizări","Completion","Watch time","Likes"].map(h=>(
                    <th key={h} style={{padding:"7px 8px",textAlign:h==="Titlu"?"left":"right",fontSize:10,fontWeight:500,color:C.text3,textTransform:"uppercase",letterSpacing:"0.06em",whiteSpace:"nowrap"}}>{h}</th>
                  ))}
                </tr></thead>
                <tbody>{topV.map((v,i)=>(
                  <tr key={i} style={{borderBottom:`1px solid ${C.border}`}}>
                    <td style={{padding:"8px",color:C.text3,textAlign:"right"}}>{i+1}</td>
                    <td style={{padding:"8px",maxWidth:230,overflow:"hidden",textOverflow:"ellipsis",whiteSpace:"nowrap",color:C.text}} title={v.title}>{v.title}</td>
                    <td style={{padding:"8px",textAlign:"right"}}><span style={{fontSize:10,fontWeight:500,padding:"2px 6px",borderRadius:20,background:v.type==="Short"?C.blueL:C.purpleL,color:v.type==="Short"?C.blueD:C.purpleD}}>{v.type}</span></td>
                    <td style={{padding:"8px",textAlign:"right",color:C.text2}}>{fN(v.views)}</td>
                    <td style={{padding:"8px",textAlign:"right",color:C.text2}}>{fP(v.completion)}</td>
                    <td style={{padding:"8px",textAlign:"right",color:C.text2}}>{fN(v.watchtime)} min</td>
                    <td style={{padding:"8px",textAlign:"right",color:C.text2}}>{v.likes}</td>
                  </tr>
                ))}</tbody>
              </table>
            </div>
          </Cd>
        </div>)}

        {tab==="audience"&&(<div>
          <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:14,marginBottom:18}}>
            <Cd title="Vârstă + gen">
              <ResponsiveContainer width="100%" height={240}>
                <BarChart data={audByAge}>
                  <XAxis dataKey="age" tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false}/>
                  <YAxis tick={{fontSize:11,fill:C.text3}} axisLine={false} tickLine={false} tickFormatter={v=>v+"%"}/>
                  <Tooltip content={TT}/>
                  <Legend wrapperStyle={{fontSize:11,color:C.text2}}/>
                  <Bar dataKey="female" name="Feminin" stackId="a" fill="#ED93B1"/>
                  <Bar dataKey="male" name="Masculin" stackId="a" fill={C.blue} radius={[3,3,0,0]}/>
                </BarChart>
              </ResponsiveContainer>
            </Cd>
            <Cd title="Distribuție pe vârstă">
              <ResponsiveContainer width="100%" height={240}>
                <PieChart>
                  <Pie data={audByAge.filter(a=>a.total>0)} dataKey="total" nameKey="age" cx="50%" cy="50%" outerRadius={80} innerRadius={42} label={({age,total})=>total>5?`${age}: ${total.toFixed(0)}%`:""} labelLine={false}>
                    {audByAge.map((_,i)=><Cell key={i} fill={PC[i%PC.length]}/>)}
                  </Pie>
                  <Tooltip content={TT} formatter={v=>fP(v)}/>
                </PieChart>
              </ResponsiveContainer>
            </Cd>
          </div>
          <IB type="danger" title="Gap major: audiența vizată vs audiența reală" body="Targetul: 16–35 ani. Realitate: 45+ ani = 55,7% din audiență. 25–34 ani = 6,7% total."/>
          <IB type="info" title="Oportunitate neexploatată" body="Publicul 45+ e subservit în nișa istorică YouTube. Dacă engagement-ul lor e bun, poate fi un avantaj competitiv real față de creatorii care vizează exclusiv tinerii."/>
        </div>)}

        {tab==="traffic"&&(<div>
          <div style={{display:"grid",gridTemplateColumns:"1fr 1fr",gap:14,marginBottom:18}}>
            <Cd title="Distribuție surse">
              <ResponsiveContainer width="100%" height={230}>
                <PieChart>
                  <Pie data={traffic.slice(0,7).map(t=>({name:TL[t.source]||t.source,value:t.views}))} dataKey="value" cx="50%" cy="50%" outerRadius={82} innerRadius={44}>
                    {traffic.slice(0,7).map((_,i)=><Cell key={i} fill={TC[i%TC.length]}/>)}
                  </Pie>
                  <Tooltip content={TT}/>
                  <Legend wrapperStyle={{fontSize:11,color:C.text2}}/>
                </PieChart>
              </ResponsiveContainer>
            </Cd>
            <Cd title="Vizualizări per sursă">
              {traffic.map((t,i)=><PB key={i} label={TL[t.source]||t.source} value={t.views} max={maxT} color={TC[i%TC.length]}/>)}
            </Cd>
          </div>
          <IB type="warn" title="Trafic din abonați scăzut (2%)" body="Abonații aduc puțin din total. Thumbnails și titluri optimizate pentru abonații existenți pot crește semnificativ această sursă."/>
          <IB type="success" title="YT Search — al doilea canal (18%)" body={`${fN(traffic.find(t=>t.source==="YT_SEARCH")?.views||0)} vizualizări din căutare. Cel mai durabil tip de trafic — crește organic cu fiecare video publicat.`}/>
        </div>)}

      </div>
    </div>
  );
}

export default function App(){
  const[data,setData]=useState(null);
  const[analytics,setAnalytics]=useState(null);
  const[fileName,setFileName]=useState("");
  const load=(raw,name)=>{setData(raw);setFileName(name);setAnalytics(compute(raw));};
  const reset=()=>{setData(null);setAnalytics(null);setFileName("");};
  if(!analytics)return<UploadScreen onLoad={load}/>;
  return<Dashboard analytics={analytics} fileName={fileName} onReset={reset}/>;
}
