import React from "react";
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

const Section = ({ children, className = "" }) => (
  <section className={`relative px-6 py-24 sm:px-8 lg:px-12 ${className}`}>{children}</section>
);

const Container = ({ children, className = "" }) => (
  <div className={`mx-auto w-full max-w-7xl ${className}`}>{children}</div>
);

const Icon = ({ name = "dot", className = "h-5 w-5" }) => {
  const common = { className, viewBox: "0 0 24 24", fill: "none", stroke: "currentColor", strokeWidth: 2, strokeLinecap: "round", strokeLinejoin: "round" };
  const icons = {
    arrow: <svg {...common}><path d="M5 12h14" /><path d="m13 5 7 7-7 7" /></svg>,
    chart: <svg {...common}><path d="M4 19V5" /><path d="M4 19h16" /><path d="M8 15l3-4 3 2 4-7" /></svg>,
    building: <svg {...common}><path d="M4 21V5a2 2 0 0 1 2-2h9a2 2 0 0 1 2 2v16" /><path d="M9 21v-6h4v6" /><path d="M8 7h1" /><path d="M12 7h1" /><path d="M8 11h1" /><path d="M12 11h1" /><path d="M3 21h18" /></svg>,
    check: <svg {...common}><path d="M20 6 9 17l-5-5" /></svg>,
    clock: <svg {...common}><circle cx="12" cy="12" r="9" /><path d="M12 7v5l3 2" /></svg>,
    dollar: <svg {...common}><path d="M12 2v20" /><path d="M17 5H9.5a3.5 3.5 0 0 0 0 7H14a3.5 3.5 0 0 1 0 7H6" /></svg>,
    line: <svg {...common}><path d="M3 17l6-6 4 4 8-10" /><path d="M14 5h7v7" /></svg>,
    phone: <svg {...common}><path d="M22 16.9v3a2 2 0 0 1-2.2 2 19.8 19.8 0 0 1-8.6-3.1 19.5 19.5 0 0 1-6-6A19.8 19.8 0 0 1 2.1 4.2 2 2 0 0 1 4.1 2h3a2 2 0 0 1 2 1.7c.1.9.3 1.7.6 2.5a2 2 0 0 1-.4 2.1L8 9.6a16 16 0 0 0 6.4 6.4l1.3-1.3a2 2 0 0 1 2.1-.4c.8.3 1.6.5 2.5.6a2 2 0 0 1 1.7 2z" /></svg>,
    radar: <svg {...common}><circle cx="12" cy="12" r="9" /><path d="M12 12 18 6" /><path d="M12 3a9 9 0 0 1 9 9" /><path d="M12 7a5 5 0 0 1 5 5" /></svg>,
    alert: <svg {...common}><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z" /><path d="M12 8v4" /><path d="M12 16h.01" /></svg>,
    target: <svg {...common}><circle cx="12" cy="12" r="9" /><circle cx="12" cy="12" r="5" /><circle cx="12" cy="12" r="1" /></svg>,
    zap: <svg {...common}><path d="M13 2 3 14h8l-1 8 11-14h-8l1-6z" /></svg>,
  };
  return icons[name] || icons.dot;
};

const Badge = ({ children }) => (
  <div className="inline-flex items-center gap-2 rounded-full border border-cyan-300/20 bg-white/[0.06] px-4 py-2 text-sm font-medium text-cyan-100">
    <Icon name="radar" className="h-4 w-4 text-cyan-300" />
    {children}
  </div>
);

const MetricCard = ({ value, label, icon }) => (
  <Card className="border-white/10 bg-white/[0.06] text-white shadow-sm">
    <CardContent className="p-5">
      <div className="mb-4 flex h-10 w-10 items-center justify-center rounded-2xl bg-cyan-400/10 text-cyan-300">
        <Icon name={icon} className="h-5 w-5" />
      </div>
      <div className="text-2xl font-semibold tracking-tight">{value}</div>
      <div className="mt-1 text-sm leading-6 text-slate-400">{label}</div>
    </CardContent>
  </Card>
);

const FailureRow = ({ icon, title, copy }) => (
  <div className="group rounded-3xl border border-slate-200 bg-white p-6 shadow-sm transition hover:-translate-y-1 hover:shadow-lg">
    <div className="mb-5 flex h-12 w-12 items-center justify-center rounded-2xl bg-slate-950 text-white shadow-lg shadow-slate-950/20">
      <Icon name={icon} className="h-5 w-5" />
    </div>
    <h3 className="text-lg font-semibold text-slate-950">{title}</h3>
    <p className="mt-3 text-sm leading-7 text-slate-600">{copy}</p>
  </div>
);

const ProbePill = ({ children }) => (
  <span className="rounded-full border border-cyan-200 bg-cyan-50 px-4 py-2 text-sm font-medium text-cyan-950">{children}</span>
);

const PhoenixBenchmarkGraphic = () => {
  const stats = [
    { value: "23%", label: "No response", icon: "alert" },
    { value: "42%", label: "No human response", icon: "phone" },
    { value: "68%", label: "Primary failure: speed", icon: "clock" },
    { value: "0%", label: "Best-in-class", icon: "target" },
  ];

  return (
    <div className="relative overflow-hidden rounded-[2rem] border border-cyan-300/20 bg-[linear-gradient(135deg,#06111f_0%,#08263a_48%,#03101d_100%)] p-6 shadow-2xl shadow-slate-950/50">
      <div className="pointer-events-none absolute inset-0 bg-[linear-gradient(rgba(34,211,238,0.08)_1px,transparent_1px),linear-gradient(90deg,rgba(34,211,238,0.08)_1px,transparent_1px)] bg-[size:38px_38px] opacity-35" />
      <div className="pointer-events-none absolute right-0 top-0 h-52 w-72 rounded-full bg-cyan-400/15 blur-3xl" />
      <div className="pointer-events-none absolute bottom-0 right-0 h-32 w-full bg-[linear-gradient(180deg,transparent,rgba(14,165,233,0.12))]" />

      <div className="relative">
        <div className="mb-6 flex items-center justify-between gap-4">
          <div>
            <p className="text-xs font-semibold uppercase tracking-[0.28em] text-cyan-300">Market benchmark</p>
            <h3 className="mt-3 text-2xl font-semibold tracking-tight text-white sm:text-3xl">Phoenix Leasing Responsiveness Snapshot</h3>
          </div>
          <div className="hidden rounded-full border border-cyan-300/20 bg-cyan-300/10 px-3 py-1 text-xs font-medium text-cyan-100 sm:block">100+ properties</div>
        </div>

        <div className="grid gap-3 sm:grid-cols-2">
          {stats.map((stat) => (
            <div key={stat.label} className="rounded-3xl border border-cyan-200/20 bg-white/[0.055] p-5 backdrop-blur-sm">
              <div className="mb-5 flex h-11 w-11 items-center justify-center rounded-2xl bg-cyan-300/10 text-cyan-300">
                <Icon name={stat.icon} className="h-5 w-5" />
              </div>
              <div className="text-5xl font-semibold tracking-[-0.04em] text-cyan-300">{stat.value}</div>
              <p className="mt-2 text-base font-medium text-white">{stat.label}</p>
            </div>
          ))}
        </div>

        <div className="mt-5 flex items-center gap-3 border-t border-cyan-200/15 pt-4 text-xs uppercase tracking-[0.18em] text-slate-400">
          <Icon name="check" className="h-4 w-4 text-cyan-300" />
          Real properties · External probes · Phoenix benchmark
        </div>
      </div>
    </div>
  );
};

const Logo = ({ className = "h-12", tagline = true }) => (
  <div className={`inline-flex items-center ${className}`} aria-label="LeaseNOI logo">
    <svg viewBox="0 0 520 160" className="h-full w-auto" role="img">
      <title>LeaseNOI</title>
      <defs>
        <linearGradient id="logoMetal" x1="0" y1="0" x2="0" y2="1">
          <stop offset="0%" stopColor="#ffffff" />
          <stop offset="48%" stopColor="#d8dde3" />
          <stop offset="100%" stopColor="#8e98a3" />
        </linearGradient>
        <filter id="logoShadow" x="-20%" y="-20%" width="140%" height="150%">
          <feDropShadow dx="0" dy="5" stdDeviation="3" floodColor="#000000" floodOpacity="0.45" />
        </filter>
      </defs>

      <g filter="url(#logoShadow)">
        <path d="M175 66 C230 22 330 20 398 71" fill="none" stroke="url(#logoMetal)" strokeWidth="6" strokeLinecap="round" />
        <path d="M145 83 C235 46 355 43 454 88" fill="none" stroke="url(#logoMetal)" strokeWidth="9" strokeLinecap="round" opacity="0.95" />
        <path d="M165 91 C250 72 365 73 462 99" fill="none" stroke="#ffffff" strokeWidth="3" strokeLinecap="round" opacity="0.8" />

        <g fill="url(#logoMetal)" stroke="#111827" strokeWidth="2">
          <path d="M205 74h30v42h-30z" />
          <path d="M244 50h38v66h-38z" />
          <path d="M293 22h42v94h-42z" />
          <path d="M346 58h42v58h-42z" />
        </g>
        <g fill="#111827" opacity="0.75">
          <rect x="215" y="84" width="11" height="4" rx="1" />
          <rect x="215" y="96" width="11" height="4" rx="1" />
          <rect x="256" y="65" width="13" height="4" rx="1" />
          <rect x="256" y="79" width="13" height="4" rx="1" />
          <rect x="256" y="93" width="13" height="4" rx="1" />
          <rect x="307" y="40" width="13" height="4" rx="1" />
          <rect x="307" y="55" width="13" height="4" rx="1" />
          <rect x="307" y="70" width="13" height="4" rx="1" />
          <rect x="358" y="76" width="14" height="4" rx="1" />
          <rect x="358" y="90" width="14" height="4" rx="1" />
        </g>
      </g>

      <text x="20" y="126" fontFamily="Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, Segoe UI, sans-serif" fontSize="66" fontWeight="900" fontStyle="italic" letterSpacing="-4" fill="url(#logoMetal)" stroke="#0f172a" strokeWidth="2" paintOrder="stroke fill" filter="url(#logoShadow)">LeaseNOI</text>
      {tagline && <text x="88" y="151" fontFamily="Inter, ui-sans-serif, system-ui, sans-serif" fontSize="18" fontWeight="600" fill="#e5e7eb" opacity="0.95">Fix the System. Capture the NOI.</text>}
    </svg>
  </div>
);

const pricingPlans = [
  {
    name: "Core",
    price: "$199",
    features: [
      "Continuous monitoring across email and web channels",
      "Monthly reports with competitive ranking",
      "Channel health alerts",
      "Response-time and follow-up testing",
    ],
  },
  {
    name: "Pro",
    price: "$399",
    features: [
      "Everything in Core",
      "Phone and voicemail testing",
      "Leasing agent rubric scoring",
      "SMS channel audits",
      "Prospect question and CTA analysis",
      "Human + AI, leasing agent conversation and analysis",
    ],
  },
];

const TALLY_FORM_URL = "https://tally.so/r/gDYjkP";

const TallyForm = () => (
  <div className="rounded-[2rem] bg-white p-6 text-slate-950 shadow-2xl shadow-slate-900/20 sm:p-8">
    <div>
      <p className="text-sm font-semibold uppercase tracking-[0.18em] text-cyan-700">Free property audit</p>
      <h3 className="mt-2 text-2xl font-semibold tracking-tight">Tell us where to look</h3>
      
    </div>

    <a
      href={TALLY_FORM_URL}
      target="_blank"
      rel="noreferrer"
      className="mt-7 inline-flex w-full items-center justify-center rounded-full bg-slate-950 px-7 py-4 text-base font-semibold text-white transition hover:bg-slate-800"
    >
      Get Started <span className="ml-2">→</span>
    </a>

    <p className="mt-4 text-center text-xs leading-5 text-slate-500">
      No spam. No obligation. Just visibility into where your leasing process may be breaking down.
    </p>
  </div>
);

export default function LeaseNOILandingPage() {
  return (
    <main className="min-h-screen overflow-hidden bg-slate-50 text-slate-950 antialiased">
      <div className="relative overflow-hidden bg-[linear-gradient(180deg,#07111f_0%,#0f172a_100%)]">
        <div className="pointer-events-none absolute left-1/2 top-[-220px] h-[620px] w-[620px] -translate-x-1/2 rounded-full bg-cyan-400/10 blur-3xl" />

        <header className="relative z-20 px-6 pt-5 sm:px-8 lg:px-12">
          <Container className="flex items-center justify-between border-b border-white/10 pb-3">
            <div className="flex items-center gap-3 text-white">
              <Logo className="h-16 text-white" />
            </div>
            <Button className="hidden rounded-full bg-white px-5 font-semibold text-slate-950 hover:bg-cyan-50 sm:inline-flex">
              See where your property ranks
            </Button>
          </Container>
        </header>

        <Section className="relative z-10 pb-16 pt-6 text-white sm:pt-8">
          <Container className="grid items-center gap-10 lg:grid-cols-[1.02fr_0.98fr]">
            <div>
              <Badge>Visibility into hidden NOI leakage</Badge>
              <h1 className="mt-5 max-w-4xl text-5xl font-semibold leading-[0.98] tracking-[-0.055em] text-white sm:text-6xl xl:text-7xl">
                Most multifamily owners think leasing is functioning reasonably well. The data suggests otherwise.
              </h1>
              <div className="mt-5 max-w-2xl space-y-4 text-lg leading-7 text-slate-300 sm:text-xl sm:leading-8">
                <p>23% of properties we tested never responded to a leasing inquiry.</p>
                <p>42% never produced a human response.</p>
                <p>Most of these failures never appear in internal reporting—but they directly impact occupancy, NOI, and asset value.</p>
              </div>
              <div className="mt-6 flex flex-col gap-4 sm:flex-row">
                <Button size="lg" className="rounded-full bg-cyan-300 px-7 text-base font-semibold text-slate-950 hover:bg-cyan-200">
                  See where your property ranks <Icon name="arrow" className="ml-2 h-4 w-4" />
                </Button>
              </div>
              <p className="mt-6 max-w-2xl text-sm leading-6 text-slate-400">
                We tested 100+ multifamily properties in Phoenix using limited external probes. The failure rates were significantly worse than expected.
              </p>
            </div>

            <div className="relative lg:-mr-8">
              <div className="absolute -inset-6 rounded-[2rem] bg-cyan-400/10 blur-2xl" />
              <PhoenixBenchmarkGraphic />
              <p className="mt-3 text-sm leading-6 text-slate-400">
                Phoenix Leasing Responsiveness Snapshot based on external probe testing.
              </p>
            </div>
          </Container>
        </Section>
      </div>

      <Section className="relative z-10 bg-white">
        <Container>
          <div className="grid gap-12 lg:grid-cols-[0.85fr_1.15fr] lg:items-start">
            <div>
              <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-700">The hidden problem</p>
              <h2 className="mt-4 text-4xl font-semibold tracking-tight text-slate-950 sm:text-5xl">Most leasing failures happen before ownership ever sees them</h2>
            </div>
            <div className="space-y-5 text-xl leading-9 text-slate-700">
              <p>Calls go unanswered.</p>
              <p>Leads never reach a human.</p>
              <p>Follow-up breaks silently.</p>
              <p className="text-slate-600">And because these failures happen before meaningful engagement, they rarely appear in internal reporting.</p>
              <p className="font-semibold text-slate-950">Most owners are optimizing the front of the funnel while flying blind on whether prospects ever reach a real leasing conversation.</p>
            </div>
          </div>
          <div className="mt-12 grid gap-5 md:grid-cols-4">
            <FailureRow icon="phone" title="Marketing spend" copy="Demand is expensive to generate, but owners often cannot see whether that demand reaches a real leasing conversation." />
            <FailureRow icon="zap" title="Staffing" copy="Leasing payroll only creates value if leads are handled quickly, consistently, and through to next steps." />
            <FailureRow icon="dollar" title="Concessions" copy="Owners may adjust pricing or concessions while the real leakage is hidden inside execution." />
            <FailureRow icon="building" title="Amenities" copy="Asset upgrades drive demand, but execution failures can prevent that demand from converting." />
          </div>
        </Container>
      </Section>

      <Section className="bg-slate-100">
        <Container className="grid gap-12 lg:grid-cols-[1fr_1fr] lg:items-center">
          <div>
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-700">Financial impact</p>
            <h2 className="mt-4 text-4xl font-semibold tracking-tight text-slate-950 sm:text-5xl">Small leasing failures create disproportionate NOI damage</h2>
            <div className="mt-6 space-y-4 text-lg leading-8 text-slate-600">
              <p>Owners can spend aggressively on marketing, staffing, concessions, and amenities—and still lose leases because prospects never receive a response, never reach a human, or never receive meaningful follow-up.</p>
              <p>The economics compound quickly.</p>
              <p>A leasing process converting at 8% (industry average) instead of 16% (top performers) can materially impact occupancy, concession pressure, NOI, refinance leverage, and asset valuation.</p>
              <p>Most owners never see where that leakage actually starts.</p>
            </div>
          </div>
          <div className="rounded-[2rem] bg-white p-6 shadow-xl shadow-slate-200/80">
            {[
              ["183 units", "$1,600 average rent"],
              ["8% vacancy", "~$280,000 annual vacancy exposure"],
              ["$20K–$60K+", "Potential NOI improvement from modest execution gains"],
              ["$300K–$1M+", "Potential asset value impact"],
            ].map(([amount, label]) => (
              <div key={amount} className="flex items-center gap-5 border-b border-slate-100 py-6 first:pt-2 last:border-0 last:pb-2">
                <div className="min-w-36 text-3xl font-semibold tracking-tight text-slate-950">{amount}</div>
                <div className="text-base leading-7 text-slate-600">{label}</div>
              </div>
            ))}
          </div>
        </Container>
      </Section>

      <Section className="bg-slate-950 text-white">
        <Container>
          <div className="mx-auto max-w-3xl text-center">
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-300">Market data</p>
            <h2 className="mt-4 text-4xl font-semibold tracking-tight sm:text-5xl">The leasing execution problem is larger than most owners realize</h2>
          </div>
          <div className="mt-14 grid gap-6 md:grid-cols-3">
            {[
              ["80%", "scored as underperformers"],
              ["0", "reached best-in-class performance"],
              ["42%", "never produced a human response"],
            ].map(([value, label]) => (
              <Card key={value} className="border-white/10 bg-white/[0.06] text-white shadow-2xl shadow-slate-950/40 backdrop-blur-xl">
                <CardContent className="p-8 text-center">
                  <div className="text-5xl font-semibold tracking-tight text-cyan-300">{value}</div>
                  <p className="mt-4 text-lg leading-8 text-slate-300">{label}</p>
                </CardContent>
              </Card>
            ))}
          </div>
          <p className="mx-auto mt-10 max-w-3xl text-center text-lg leading-8 text-slate-300">
            Most failures occurred before meaningful engagement ever happened—and this was from limited probing, not full operational audits. The visibility gap is real.
          </p>
        </Container>
      </Section>

      <Section className="bg-white">
        <Container className="grid gap-12 lg:grid-cols-[0.9fr_1.1fr] lg:items-center">
          <div>
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-700">Operator insight</p>
            <h2 className="mt-4 text-4xl font-semibold tracking-tight text-slate-950 sm:text-5xl">This was the single highest ROI leasing lever we saw once we had visibility into it</h2>
          </div>
          <div className="space-y-5 text-lg leading-8 text-slate-600">
            <p>As operators and investors, we found that the biggest leasing gains rarely came from pricing or concessions.</p>
            <p>They came from something simpler: making sure leads were actually being worked consistently.</p>
            <p>Once we had visibility into missed inquiries, weak follow-up, and execution breakdowns, the operational issues became obvious—and fixable.</p>
            <p className="font-semibold text-slate-950">Leasing execution can’t improve until ownership can actually see where it’s breaking.This was one of those situations where 20% of our efforts generated 80% of our gains.</p>
          </div>
        </Container>
      </Section>

      <Section className="bg-slate-50">
        <Container className="grid gap-12 lg:grid-cols-[0.95fr_1.05fr] lg:items-center">
          <div>
            <p className="text-sm font-semibold uppercase tracking-[0.2em] text-cyan-700">What LeaseNOI surfaces</p>
            <h2 className="mt-4 text-4xl font-semibold tracking-tight text-slate-950 sm:text-5xl">We surface the failures owners usually never see</h2>
            <p className="mt-6 text-lg leading-8 text-slate-600">
              LeaseNOI exposes missed inquiries, weak follow-up, response failures, competitive execution gaps, and hidden conversion leakage before those problems show up as occupancy loss.
            </p>
          </div>
          <div className="grid gap-4">
            {[
              "Missed inquiries",
              "Weak follow-up",
              "Response failures",
              "Competitive execution gaps",
              "Hidden conversion leakage",
            ].map((item) => (
              <div key={item} className="flex items-start gap-4 rounded-3xl border border-slate-200 bg-white p-5 shadow-sm">
                <Icon name="check" className="mt-1 h-5 w-5 shrink-0 text-cyan-700" />
                <p className="text-lg font-medium leading-7 text-slate-800">{item}</p>
              </div>
            ))}
          </div>
        </Container>
      </Section>

      <Section className="bg-slate-950 pb-12 text-white">
        <Container>
          <div className="relative overflow-hidden rounded-[2.5rem] border border-white/10 bg-gradient-to-br from-cyan-300 to-blue-500 p-8 text-slate-950 shadow-2xl shadow-slate-950/40 sm:p-12 lg:p-16">
            <div className="absolute right-[-10%] top-[-40%] h-80 w-80 rounded-full bg-white/30 blur-3xl" />
            <div className="relative grid gap-10 lg:grid-cols-[0.9fr_1.1fr] lg:items-start">
              <div>
                <h2 className="text-4xl font-semibold tracking-tight sm:text-6xl">See where your leasing process is failing before it costs you another lease</h2>
                <div className="mt-6 space-y-4 text-lg leading-8 text-slate-900/75">
                  <p>Most owners have very little external visibility into whether leasing execution is actually happening the way they believe it is.</p>
                  <p>LeaseNOI helps surface missed demand, broken execution, follow-up failures, competitive gaps, and hidden NOI leakage.</p>
                  <p>So ownership can finally see—and fix—the operational issues impacting leasing performance.</p>
                </div>
              </div>

              <TallyForm />
            </div>
          </div>
          <footer className="flex flex-col items-center justify-between gap-4 py-10 text-sm text-slate-500 sm:flex-row">
            <div className="flex items-center gap-3 text-slate-300">
              <Logo className="h-20 text-slate-300" />
            </div>
            <div>Visibility into hidden NOI leakage.</div>
          </footer>
        </Container>
      </Section>
    </main>
  );
}
