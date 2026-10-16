<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Vetpro Consultancy | Farm Equipment</title>
  <style>
    :root {
      --green: #174f3b;
      --light-green: #eaf2e5;
      --lime: #d9ed76;
      --bg: #f7f9f5;
      --text: #192b22;
      --muted: #68766f;
      --white: #fff;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font: 14px Arial, sans-serif;
    }

    button, input, select, textarea { font: inherit; }
    button, a { cursor: pointer; }
    a { color: inherit; text-decoration: none; }
    .announcement {
      padding: 10px;
      text-align: center;
      color: white;
      background: var(--green);
      font-size: 12px;
    }
    header {
      background: white;
      padding: 18px 6%;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
      border-bottom: 1px solid #e3e9e1;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    .brand { display: flex; align-items: center; gap: 10px; }
    .logo {
      background: var(--green);
      color: var(--lime);
      border-radius: 10px;
      padding: 12px;
      font-size: 20px;
      font-weight: 800;
    }
    .brand strong { font-size: 18px; letter-spacing: 2px; }
    .brand small { display: block; margin-top: 4px; letter-spacing: 3px; }
    nav { display: flex; gap: 22px; }
    nav a { font-size: 12px; font-weight: bold; }
    nav a:hover { color: #43855e; }
    .header-actions { display: flex; gap: 8px; }
    button {
      border: 0;
      border-radius: 8px;
      padding: 11px 14px;
    }
    .primary { background: var(--green); color: white; }
    .primary:hover { background: #28684c; }
    .secondary { background: white; border: 1px solid #d8e2d5; }
    .hidden { display: none !important; }

    .hero {
      padding: 65px 8%;
      display: grid;
      grid-template-columns: 1fr 1fr;
      align-items: center;
      gap: 45px;
    }
    .eyebrow {
      color: #36734f;
      font-size: 11px;
      font-weight: bold;
      letter-spacing: 2px;
    }
    h1 {
      font-size: clamp(38px, 5vw, 65px);
      line-height: 1.08;
      letter-spacing: -2px;
      margin: 22px 0;
    }
    h1 em { color: var(--green); font-style: normal; }
    .hero p { color: var(--muted); line-height: 1.9; max-width: 470px; }
    .hero-buttons { display: flex; flex-wrap: wrap; gap: 12px; margin-top: 25px; }
    .hero-image {
      min-height: 360px;
      border-radius: 110px 18px 18px 18px;
      background: url("https://images.unsplash.com/photo-1516467508483-a7212febe31a?auto=format&fit=crop&w=1100&q=85") center/cover;
    }
    .benefits {
      margin: 0 6%;
      background: white;
      border: 1px solid #e3e9e1;
      border-radius: 12px;
      padding: 23px;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 15px;
    }
    .benefits strong { display: block; margin-bottom: 6
