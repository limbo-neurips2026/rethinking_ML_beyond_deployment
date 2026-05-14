+++
title = "Beyond Time-Zero Performance @ NeurIPS 2026"
+++

<style>
.topic-grid,
.track-grid,
.people-grid,
.advisor-grid {
    display: grid;
    grid-template-columns: 1fr;
    gap: 1rem;
    margin: 1.5rem 0 2rem;
}

.topic-card,
.track-card,
.person-card,
.advisor-card {
    background: rgba(255, 255, 255, 0.62);
    border: 1px solid rgba(0, 0, 0, 0.08);
    border-radius: 8px;
    padding: 1rem;
}

.topic-card h4,
.track-card h4,
.person-card h4,
.advisor-card h4 {
    margin: 0 0 0.35rem;
}

.topic-card p,
.track-card p,
.person-card p,
.advisor-card p {
    margin: 0;
}

.person-role,
.person-affiliation,
.advisor-affiliation {
    color: #666;
    font-size: 0.92rem;
    line-height: 1.45;
}

.speaker-grid {
    gap: 2.5rem 1.5rem;
}

.speaker-grid .person-card {
    background: transparent;
    border: 0;
    padding: 0.5rem;
    text-align: center;
}

.speaker-photo {
    width: min(220px, 64vw);
    aspect-ratio: 1;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    margin: 0 auto 1rem;
}

.speaker-grid .person-card h4 {
    font-size: clamp(1.45rem, 4.8vw, 2rem);
    margin-bottom: 0.6rem;
}

.speaker-grid .person-affiliation {
    color: #333;
    font-size: 1rem;
}

#schedule table td:first-child,
#schedule table th:first-child {
    white-space: nowrap;
    width: 1%;
}

.pc-grid {
    column-count: 1;
    column-gap: 3rem;
    margin-top: 1.5rem;
}

.pc-member {
    break-inside: avoid;
    margin-bottom: 0.4rem;
}

.pc-affiliation {
    color: #666;
}

@media (min-width: 760px) {
    .topic-grid,
    .track-grid,
    .people-grid,
    .advisor-grid {
        grid-template-columns: repeat(2, 1fr);
    }
}

@media (min-width: 1000px) {
    .topic-grid,
    .people-grid {
        grid-template-columns: repeat(3, 1fr);
    }

    .pc-grid {
        column-count: 2;
    }
}
</style>

---

<section id="about">

## About {#about}

Standard ML evaluation assumes a stationary world: a fixed test distribution, a fixed dataset, and a fixed notion of correctness. Deployed clinical systems violate all three. Patient populations drift, hardware and protocols evolve, individual records may need to be removed, and clinician feedback continually reshapes what counts as a correct prediction.

This workshop brings together researchers working on adaptable, maintainable, and interactive machine learning systems for healthcare. We focus on post-deployment behavior: models that can adapt under distribution shift, support verifiable unlearning, expose uncertainty, and be audited or corrected through human feedback without destabilizing learned behavior.

Our goal is to build shared problem formulations, evaluation protocols, and benchmarks for healthcare ML systems that change over time. The workshop is method-first, with healthcare as the stress test: data scarcity, privacy withdrawal, clinical oversight, safety constraints, and regulation make post-deployment reliability unavoidable.

### Topics

<div class="topic-grid">
<div class="topic-card"><h4>Continual and Test-Time Adaptation</h4><p>Methods for models that update under changing patient populations, clinical workflows, hardware, and acquisition protocols.</p></div>
<div class="topic-card"><h4>Machine Unlearning</h4><p>Privacy-compliant removal of patient data, auditability, and verifiable guarantees under limited clinical data.</p></div>
<div class="topic-card"><h4>Interactive Model Steering</h4><p>Clinician feedback, preference-based updates, counterfactual interventions, and concept-level control.</p></div>
<div class="topic-card"><h4>Post-Deployment Evaluation</h4><p>Benchmarks and protocols for distribution shift, continual adaptation, unlearning audits, and human-in-the-loop systems.</p></div>
<div class="topic-card"><h4>Trustworthy Clinical Deployment</h4><p>Robustness, calibrated uncertainty, monitoring, regulatory constraints, and safe lifecycle management.</p></div>
<div class="topic-card"><h4>Clinical Translation</h4><p>Work that connects core ML methods with real-world clinical settings, deployment constraints, and clinician oversight.</p></div>
</div>

</section>

---

<section id="key-info">

## Key Info {#key-info}

### Important Dates

Please note that all deadlines are Anywhere on Earth (AOE). Dates will be updated after workshop acceptance.

- **Submission site:** OpenReview, to be announced
- **Submission deadline:** To be announced
- **Author notification:** Before September 29, 2026
- **Workshop date:** To be announced
- **Expected attendance:** Approximately 300 attendees

### Format

The workshop will feature invited talks, selected spotlight talks, two poster sessions, a moderated panel, an open Q&A discussion, and closing awards. Reviewing will be double-blind via OpenReview, with at least three reviews per submission and conflict-of-interest handling at both organizer and reviewer levels.

</section>

---

<section id="call-for-papers">

## Call for Papers {#call-for-papers}

We invite submissions on machine learning methods and clinical translations for systems that must remain reliable after deployment. Relevant topics include, but are not limited to:

- Continual and lifelong learning for evolving clinical populations
- Test-time adaptation and domain adaptation in healthcare
- Machine unlearning for privacy-compliant patient withdrawal
- Robustness to hardware, site, protocol, and population shifts
- Clinician-in-the-loop model steering and auditing
- Counterfactual reasoning and concept-level interventions
- Post-deployment monitoring, uncertainty, and lifecycle evaluation
- Benchmarks for adaptation, unlearning, steering, and clinical drift

### Submission Tracks

<div class="track-grid">
<div class="track-card"><h4>Tiny Papers</h4><p>Up to 4 pages for early-stage ideas, negative results, position pieces, and focused technical contributions, with priority for emerging and under-represented authors.</p></div>
<div class="track-card"><h4>Proceedings Track</h4><p>Up to 8 pages for full, unpublished work forming the core scientific program through posters and selected spotlights.</p></div>
<div class="track-card"><h4>Datasets & Benchmarks Track</h4><p>Up to 8 pages for curated datasets, standardized post-deployment evaluation protocols, reproducible benchmarks, and baselines.</p></div>
</div>

Proceedings-track and Datasets & Benchmarks papers are planned for a dedicated PMLR workshop volume. We are also exploring an editorial summarizing the scientific outcomes and research agenda of the workshop.

### Review

- **Review model:** Double-blind
- **Platform:** OpenReview
- **Anonymization:** Required for all submissions
- **Reviews:** At least three reviews per submission
- **Conflicts:** Organizers and reviewers will recuse themselves from conflicted submissions

</section>

---

<section id="accepted-papers">

## Accepted Papers {#accepted-papers}

</section>

---

<section id="awards">

## Awards {#awards}

</section>

---

<section id="schedule">

## Schedule {#schedule}

| Time | Session | Lead / Speaker |
| --- | --- | --- |
| 09:00-09:15 | Opening Remarks | Organizers |
| 09:15-09:35 | Invited Talk I | Irene Chen |
| 09:40-10:00 | Invited Talk II | Enzo Ferrante |
| 10:00-10:10 | Spotlight Talk I - Selected Submission | Presenter 1 |
| 10:10-10:20 | Spotlight Talk II - Selected Submission | Presenter 2 |
| 10:20-11:00 | Coffee Break & Poster Session I | Poster Presenters |
| 11:00-11:20 | Invited Talk III | Razvan Pascanu |
| 11:25-11:45 | Invited Talk IV | Olivier Salvado |
| 11:45-12:30 | Panel Discussion: Challenges of Deploying and Adapting Healthcare AI | Moderators / Panelists |
| 12:30-14:00 | Lunch & Networking | - |
| 14:00-14:20 | Invited Talk V | Yarin Gal |
| 14:25-14:45 | Invited Talk VI | Melissa McCradden |
| 14:45-14:55 | Spotlight Talk III - Selected Submission | Presenter 3 |
| 14:55-15:05 | Spotlight Talk IV - Selected Submission | Presenter 4 |
| 15:05-15:45 | Coffee Break & Poster Session II | Poster Presenters |
| 15:45-16:15 | Open Q&A and Discussion | Session Chair |
| 16:15-16:30 | Closing Remarks & Awards | Organizers |

</section>

---

<section id="speakers">

## Confirmed Speakers {#confirmed-speakers}

<div class="people-grid speaker-grid">
<div class="person-card"><img class="speaker-photo" src="img/speakers/irene-chen.jpeg" alt="Irene Chen"><h4>Irene Chen</h4><p class="person-affiliation">UC Berkeley, US</p><p class="person-role">Speaker & Panelist</p></div>
<div class="person-card"><img class="speaker-photo" src="img/speakers/enzo-ferrante.jpeg" alt="Enzo Ferrante"><h4>Enzo Ferrante</h4><p class="person-affiliation">Universidad de Buenos Aires, AR</p><p class="person-role">Speaker & Panelist</p></div>
<div class="person-card"><img class="speaker-photo" src="img/speakers/razvan-pascanu.jpeg" alt="Razvan Pascanu"><h4>Razvan Pascanu</h4><p class="person-affiliation">Google DeepMind and Mila, UK</p><p class="person-role">Speaker & Panelist</p></div>
<div class="person-card"><img class="speaker-photo" src="img/speakers/olivier-salvado.jpeg" alt="Olivier Salvado"><h4>Olivier Salvado</h4><p class="person-affiliation">Queensland University of Technology, AU</p><p class="person-role">Speaker & Panelist</p></div>
<div class="person-card"><img class="speaker-photo" src="img/speakers/yarin-gal.jpeg" alt="Yarin Gal"><h4>Yarin Gal</h4><p class="person-affiliation">University of Oxford, UK</p><p class="person-role">Speaker & Panelist</p></div>
<div class="person-card"><img class="speaker-photo" src="img/speakers/melissa-mccradden.webp" alt="Melissa McCradden"><h4>Melissa McCradden</h4><p class="person-affiliation">University of Adelaide, AU</p><p class="person-role">Speaker & Panelist</p></div>
</div>

</section>

---

<section id="organizers">

## Organizers {#organizers}

<div class="people-grid">
<div class="person-card"><h4>Cristina Almagro-Perez</h4><p class="person-affiliation">Harvard-MIT Health Sciences and Technology; Brigham and Women's Hospital, US</p><p class="person-role">Operations & Program Delivery Chair</p></div>
<div class="person-card"><h4>Sonia Laguna</h4><p class="person-affiliation">Apple; ETH Zurich; Max Planck Institute, FR/CH/DE</p><p class="person-role">Executive Co-Chair & Scientific Co-Chair</p></div>
<div class="person-card"><h4>Silke Muehlstedt</h4><p class="person-affiliation">ETH Zurich, CH</p><p class="person-role">Strategy, External Relations & Sponsorship Chair</p></div>
<div class="person-card"><h4>Tingrui "Ricky" Qiao</h4><p class="person-affiliation">University of Auckland, NZ</p><p class="person-role">Program Committee Chair</p></div>
<div class="person-card"><h4>Samuel Ruiperez-Campillo</h4><p class="person-affiliation">MIT Institute for Medical Engineering and Science, US</p><p class="person-role">Executive Co-Chair & Scientific Co-Chair</p></div>
</div>

### Senior Advisory Board

<div class="advisor-grid">
<div class="advisor-card"><h4>Joelle Barral</h4><p class="advisor-affiliation">Senior Director of Research & Engineering, Google DeepMind, FR</p></div>
<div class="advisor-card"><h4>Yun Sing Koh</h4><p class="advisor-affiliation">Professor, University of Auckland, NZ</p></div>
<div class="advisor-card"><h4>Rajesh Ranganath</h4><p class="advisor-affiliation">Professor, New York University, US</p></div>
<div class="advisor-card"><h4>Julia Vogt</h4><p class="advisor-affiliation">Associate Professor, ETH Zurich, CH</p></div>
</div>

</section>

---

<section id="program-committee">

## Program Committee Members {#program-committee}

<div class="pc-grid">
<div class="pc-member"><strong>Andrea Agostini</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Fabricio Arrend Torres</strong>, <span class="pc-affiliation">Rekonas</span></div>
<div class="pc-member"><strong>Sabyasachi Bandyopadhyay</strong>, <span class="pc-affiliation">Stanford University</span></div>
<div class="pc-member"><strong>Alice Bizeul</strong>, <span class="pc-affiliation">Apple</span></div>
<div class="pc-member"><strong>Irene Cannistraci</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Maria Cervera de la Rosa</strong>, <span class="pc-affiliation">Apple</span></div>
<div class="pc-member"><strong>Daphne Chopard</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Kasia Cobalczyk</strong>, <span class="pc-affiliation">University of Cambridge</span></div>
<div class="pc-member"><strong>Imant Daunhawer</strong>, <span class="pc-affiliation">kaiko.ai</span></div>
<div class="pc-member"><strong>Prasanth Ganesan</strong>, <span class="pc-affiliation">Stanford University</span></div>
<div class="pc-member"><strong>Robin Geyer</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Jorge da Silva Goncalves</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Francesco Ignazio Re</strong>, <span class="pc-affiliation">UN Operations Crisis Centre</span></div>
<div class="pc-member"><strong>Giulia Lanzillotta</strong>, <span class="pc-affiliation">RIKEN Tokyo</span></div>
<div class="pc-member"><strong>Sonia Laguna</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Heike Leutheuser</strong>, <span class="pc-affiliation">University of Bayreuth</span></div>
<div class="pc-member"><strong>Laura Manduchi</strong>, <span class="pc-affiliation">Apple</span></div>
<div class="pc-member"><strong>Ricards Marcinkevics</strong>, <span class="pc-affiliation">Zalando Data Science</span></div>
<div class="pc-member"><strong>Yang Meng</strong>, <span class="pc-affiliation">UC Irvine</span></div>
<div class="pc-member"><strong>Marcello Negri</strong>, <span class="pc-affiliation">University of Basel</span></div>
<div class="pc-member"><strong>Alizee Pace</strong>, <span class="pc-affiliation">Google DeepMind</span></div>
<div class="pc-member"><strong>Emanuele Palumbo</strong>, <span class="pc-affiliation">Apple</span></div>
<div class="pc-member"><strong>Michael Reiss</strong>, <span class="pc-affiliation">UC San Diego</span></div>
<div class="pc-member"><strong>Miguel Rodrigo</strong>, <span class="pc-affiliation">University of Valencia</span></div>
<div class="pc-member"><strong>Alain Ryser</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Maxim Samarin</strong>, <span class="pc-affiliation">Swiss Data Science Center</span></div>
<div class="pc-member"><strong>Simon Schug</strong>, <span class="pc-affiliation">New York University</span></div>
<div class="pc-member"><strong>Farrin Sofian</strong>, <span class="pc-affiliation">UC Irvine</span></div>
<div class="pc-member"><strong>Robin Van de Water</strong>, <span class="pc-affiliation">Hasso Plattner Institute</span></div>
<div class="pc-member"><strong>Moritz Vandenhirtz</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Mario Wieser</strong>, <span class="pc-affiliation">Genedata</span></div>
<div class="pc-member"><strong>Justus Will</strong>, <span class="pc-affiliation">UC Irvine</span></div>
<div class="pc-member"><strong>Simon Bohi</strong>, <span class="pc-affiliation">University of Basel</span></div>
<div class="pc-member"><strong>Paul Fischer</strong>, <span class="pc-affiliation">University of Basel</span></div>
<div class="pc-member"><strong>Sergio Munoz-Gonzalez</strong>, <span class="pc-affiliation">University of Basel</span></div>
<div class="pc-member"><strong>Simon Pezold</strong>, <span class="pc-affiliation">University of Basel</span></div>
<div class="pc-member"><strong>Sonali Andani</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
<div class="pc-member"><strong>Melanie Roschewitz</strong>, <span class="pc-affiliation">ETH Zurich</span></div>
</div>

</section>

---

<section id="contact">

## Contact {#contact}

- General inquiries: <calmagroperez@hst.harvard.edu>

</section>
