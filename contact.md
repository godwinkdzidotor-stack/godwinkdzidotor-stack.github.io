<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Contact | Godwin K. Dzidotor, PhD</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Contact Godwin K. Dzidotor, PhD — Cybersecurity Engineer, DevSecOps, Cloud Security, Network Security."
  />
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link
    href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap"
    rel="stylesheet"
  />

  <style>
    :root {
      --bg: #020617;
      --bg-soft: #0b1120;
      --card: #020617;
      --accent: #22c55e;
      --accent-soft: rgba(34, 197, 94, 0.2);
      --text-main: #e5e7eb;
      --text-muted: #9ca3af;
      --link: #58a6ff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: "Inter", system-ui, -apple-system, BlinkMacSystemFont,
        "Segoe UI", sans-serif;
      background: radial-gradient(circle at top, #0f172a 0, #020617 55%);
      color: var(--text-main);
    }

    a {
      color: var(--link);
    }

    a:hover {
      text-decoration: underline;
    }

    .page-shell {
      max-width: 980px;
      margin: 32px auto 40px;
      padding: 0 16px;
    }

    /* Top micro header (Back / Close) */
    .micro-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: #020617;
      border-radius: 14px;
      padding: 10px 14px;
      box-shadow: 0 0 18px rgba(15, 23, 42, 0.9);
      margin-bottom: 20px;
    }

    .micro-link {
      font-size: 0.9rem;
      font-weight: 500;
      text-decoration: none;
      color: #9ca3af;
      padding: 6px 10px;
      border-radius: 999px;
      border: 1px solid transparent;
      transition: background 0.18s ease, color 0.18s ease,
        box-shadow 0.18s ease, border-color 0.18s ease,
        transform 0.18s ease;
    }

    .micro-link:hover {
      background: #111827;
      color: #e5e7eb;
      box-shadow: 0 0 12px rgba(148, 163, 184, 0.45);
      border-color: var(--accent);
      transform: translateY(-1px);
      text-decoration: none;
    }

    .micro-link.danger:hover {
      border-color: #f97316;
      box-shadow: 0 0 14px rgba(248, 113, 113, 0.55);
    }

    /* Main contact card */
    .card {
      background: var(--card);
      border-radius: 18px;
      padding: 26px 20px 24px;
      text-align: center;
      box-shadow: 0 0 28px rgba(15, 23, 42, 0.95);
    }

    .card h1 {
      margin: 0 0 6px;
      font-size: 1.9rem;
      color: var(--accent);
    }

    .card p.subtitle {
      margin: 0 0 14px;
      color: var(--text-muted);
      font-size: 0.98rem;
    }

    /* Nav inside card */
    .nav-row {
      margin: 10px 0 4px;
      font-size: 0.96rem;
    }

    .nav-row a {
      color: var(--link);
      margin: 0 10px;
      text-decoration: none;
      padding: 4px 8px;
      border-radius: 999px;
      transition: background 0.18s ease, color 0.18s ease,
        transform 0.18s ease;
    }

    .nav-row a:hover {
      background: #111827;
      color: #e5e7eb;
      transform: translateY(-1px);
    }

    .nav-row a.active {
      background: var(--accent-soft);
      color: #e5e7eb;
    }

    /* Content sections */
    .content {
      margin-top: 26px;
      text-align: left;
      color: var(--text-main);
      line-height: 1.7;
      font-size: 0.97rem;
    }

    .content h2 {
      font-size: 1.2rem;
      margin-top: 0;
    }

    .content section {
      background: #020617;
      border-radius: 14px;
      padding: 18px 18px 16px;
      margin-bottom: 18px;
      box-shadow: 0 0 18px rgba(15, 23, 42, 0.8);
    }

    .content ul {
      margin-top: 8px;
      padding-left: 20px;
    }

    .content li {
      margin-bottom: 4px;
    }

    .muted {
      color: var(--text-muted);
    }

    @media (max-width: 640px) {
      .micro-header {
        flex-direction: column;
        gap: 8px;
        align-items: stretch;
      }

      .micro-header .micro-link {
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="page-shell">
    <!-- Micro header -->
    <header class="micro-header">
      <a href="https://godwinkdzidotor-stack.github.io" class="micro-link">
        ⬅ Back to Home
      </a>
      <a href="https://github.com/godwinkdzidotor-stack" class="micro-link danger">
        ✕ Close
      </a>
    </header>

    <!-- Main contact card -->
    <main class="card">
      <h1>📬 Contact &amp; Next Steps</h1>
      <p class="subtitle">
        The best ways to reach me for roles, collaboration, or technical discussions.
      </p>

      <!-- Navigation -->
      <p class="nav-row">
        <a href="https://godwinkdzidotor-stack.github.io">Home</a>
        <a href="https://godwinkdzidotor-stack.github.io/projects">Projects</a>
        <a href="https://godwinkdzidotor-stack.github.io/skills">Skills</a>
        <a href="https://godwinkdzidotor-stack.github.io/about">About</a>
        <a href="https://godwinkdzidotor-stack.github.io/contact" class="active">
          Contact
        </a>
      </p>

      <!-- Contact content -->
      <div class="content">
        <section>
          <h2>📧 Primary Contact</h2>
          <p>
            <strong>Email:</strong><br />
            <a href="mailto:godwink.dzidotor@gmail.com">
              godwink.dzidotor@gmail.com
            </a>
          </p>

          <p>
            <strong>LinkedIn:</strong><br />
            <a href="https://www.linkedin.com/in/godwink-dzidotor-phd" target="_blank" rel="noopener noreferrer">
              linkedin.com/in/godwink-dzidotor-phd
            </a>
          </p>

          <p>
            <strong>GitHub:</strong><br />
            <a href="https://github.com/godwinkdzidotor-stack" target="_blank" rel="noopener noreferrer">
              github.com/godwinkdzidotor-stack
            </a>
          </p>
        </section>

        <section>
          <h2>🤝 How I Can Help</h2>
          <p>I’m open to conversations about:</p>
          <ul>
            <li><strong>Cybersecurity Engineering / DevSecOps roles</strong></li>
            <li><strong>Cloud &amp; infrastructure security</strong> initiatives</li>
            <li>Building or improving <strong>CI/CD security pipelines</strong></li>
            <li><strong>Network security</strong> and baseline hardening projects</li>
            <li>Collaborating on <strong>education, labs, or training content</strong></li>
          </ul>

          <p class="muted">
            If you’d like to discuss a specific opportunity, including timeframes
            or constraints, feel free to include:
          </p>
          <ul>
            <li>The <strong>type of role</strong> (full-time, contract, project-based, etc.)</li>
            <li>The <strong>primary tech stack</strong> (cloud provider, tools, languages)</li>
            <li>
              How security is currently integrated into your
              <strong>SDLC or operations</strong>
            </li>
          </ul>
        </section>

        <section>
          <h2>🧪 Using This Portfolio in Interviews</h2>
          <p>
            If you arrived here from a resume or LinkedIn:
          </p>
          <ul>
            <li>
              The <strong>Projects</strong> page maps directly to the repositories I
              mention in my resume.
            </li>
            <li>
              The <strong>Skills</strong> page outlines the technologies I’ve applied
              in hands-on labs.
            </li>
            <li>
              The <strong>Home</strong> page provides a quick, recruiter-friendly
              overview.
            </li>
          </ul>

          <p class="muted">
            I’m happy to walk through any of these repos live, talk through design
            decisions, or discuss how I would extend them in a production setting.
          </p>
        </section>

        <section>
          <p>Thank you for visiting — I look forward to connecting.</p>
        </section>
      </div>
    </main>
  </div>
</body>
</html>
