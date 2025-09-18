# Лабораторная работа. Утилита WordCount

## Задача.	

 <!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Лабораторная — Тема 00: Решение алгоритмических задач</title>
  <style>
    body { font-family: Inter, "Helvetica Neue", Arial, sans-serif; line-height:1.5; padding:24px; color:#111; background:#f7fafc; }
    header { margin-bottom:20px; }
    h1 { margin:0 0 8px 0; font-size:28px; }
    h2 { margin-top:18px; }
    .card { background:white; border-radius:12px; padding:16px; box-shadow:0 6px 18px rgba(15,23,42,0.06); margin-bottom:12px; }
    pre { background:#0f172a; color:#e6eef8; padding:12px; border-radius:8px; overflow:auto; }
    code { font-family: "Courier New", monospace; }
    label { display:block; margin:8px 0 4px; font-weight:600; }
    input[type="number"] { padding:8px 10px; font-size:16px; width:140px; border-radius:8px; border:1px solid #cbd5e1; }
    button { padding:10px 14px; border-radius:10px; border:0; background:#0ea5a4; color:white; cursor:pointer; font-weight:600; }
    .row { display:flex; gap:12px; align-items:center; flex-wrap:wrap; }
    canvas { background:#ffffff; border-radius:8px; border:1px solid #e2e8f0; }
    .muted { color:#475569; font-size:14px; }
    footer { margin-top:18px; color:#475569; font-size:13px; }
  </style>
</head>
<body>
  <header>
    <h1>Тема 00 — Решение алгоритмических задач: Введение в инструменты и критерии оценки</h1>
    <div class="muted">Цель: настроить окружение, освоить ввод/вывод, написать и протестировать первую программу, проводить замеры и визуализировать результаты.</div>
  </header>

  <section class="card">
    <h2>Краткая теория</h2>
    <p><strong>Алгоритм</strong> — последовательность шагов для решения задачи. <strong>Структуры данных</strong> — способы организации данных. Критерии оценки: <em>правильность</em> и


