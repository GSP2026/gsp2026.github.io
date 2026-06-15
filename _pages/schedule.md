---
layout: page
permalink: /schedule/
title: "Program"
description: 
nav: true
nav_order: 0

top_image: /assets/img/banners/banner_oso_GSP2.png
top_image_alt: "GSP 2026 Madrid"
---

<style>
  .schedule-preview {
    margin: 2rem 0 3rem;
  }

  .schedule-preview h4 {
    margin-bottom: 0.8rem;
  }

  .schedule-note {
    margin-bottom: 1rem;
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }

  .schedule-table-wrap {
    overflow-x: auto;
  }

  .schedule-table {
    width: 100%;
    min-width: 720px;
  }

  .schedule-table th,
  .schedule-table td {
    padding: 0.95rem 1.1rem;
    vertical-align: middle;
  }

  .schedule-table .time-slot {
    white-space: nowrap;
    font-weight: 600;
  }

  .schedule-clean-card .schedule-table {
    border-collapse: separate;
    border-spacing: 0;
    overflow: hidden;
    background: #ffffff;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.06);
  }

  .schedule-clean-card th {
    background: rgba(40, 110, 180, 0.12);
    font-weight: 700;
  }

  .schedule-clean-card tr + tr td {
    border-top: 1px solid rgba(0, 0, 0, 0.07);
  }

  .schedule-clean-card .time-slot {
    background: rgba(40, 110, 180, 0.05);
  }

  .schedule-minimal-grid .schedule-table {
    border-collapse: collapse;
    background: #ffffff;
  }

  .schedule-minimal-grid th,
  .schedule-minimal-grid td {
    border: 1px solid rgba(0, 0, 0, 0.12);
  }

  .schedule-minimal-grid th {
    background: rgba(40, 110, 180, 0.1);
    font-weight: 700;
  }

  .schedule-minimal-grid .time-slot {
    background: rgba(0, 0, 0, 0.025);
  }

  .schedule-detailed .schedule-table {
    min-width: 0;
    table-layout: fixed;
    border-collapse: collapse;
    background: #ffffff;
    color: #222222;
    font-size: 0.84rem;
  }

  .schedule-detailed th,
  .schedule-detailed td {
    border: 1px solid rgba(0, 0, 0, 0.12);
    padding: 0.45rem 0.5rem;
    vertical-align: middle;
  }

  .schedule-detailed .title-heading {
    background: rgba(40, 110, 180, 0.12);
    text-align: left;
    font-weight: 700;
    font-size: 1rem;
  }

  .schedule-detailed .day-heading {
    background: rgba(40, 110, 180, 0.1);
    text-align: left;
    font-weight: 700;
  }

  .schedule-detailed .time-slot {
    width: 10%;
    background: rgba(40, 110, 180, 0.05);
    font-weight: 600;
  }

  .schedule-detailed .activity-cell {
    width: 23.33%;
  }

  .schedule-detailed .spacer-row td {
    height: 2rem;
    background: #ffffff;
  }

  .schedule-aesthetic-test .schedule-table {
    border: 1px solid rgba(0, 0, 0, 0.18);
    font-size: 8pt;
  }

  .schedule-aesthetic-test th,
  .schedule-aesthetic-test td {
    border: 0;
    padding: 0.38rem 0.42rem;
  }

  .schedule-aesthetic-test .day-heading + .day-heading,
  .schedule-aesthetic-test tbody td:nth-child(3),
  .schedule-aesthetic-test tbody td:nth-child(5) {
    border-left: 1px solid rgba(0, 0, 0, 0.16);
  }

  .schedule-aesthetic-test .time-slot {
    background: transparent;
  }

  .schedule-aesthetic-test .title-heading {
    border-bottom: 1px solid rgba(0, 0, 0, 0.18);
  }

  .schedule-aesthetic-test .spacer-row td {
    height: 2.2rem;
  }

  .schedule-dark-mode {
    display: none;
  }

  html[data-theme='dark'] .schedule-light-default {
    display: none;
  }

  html[data-theme='dark'] .schedule-dark-mode {
    display: block;
  }

  html[data-theme='dark'] .schedule-dark-mode .schedule-table {
    background: #ffffff !important;
    color: #222222 !important;
  }

  html[data-theme='dark'] .schedule-dark-mode th,
  html[data-theme='dark'] .schedule-dark-mode td {
    color: #222222 !important;
  }

  html[data-theme='dark'] .schedule-dark-mode .title-heading {
    background: rgba(40, 110, 180, 0.14) !important;
  }

  html[data-theme='dark'] .schedule-dark-mode .day-heading {
    background: rgba(40, 110, 180, 0.1) !important;
  }

  .schedule-day-cards {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1.25rem;
  }

  .schedule-day-card {
    border-radius: 18px;
    padding: 1.2rem;
    background: #ffffff;
    box-shadow: 0 10px 28px rgba(0, 0, 0, 0.06);
  }

  .schedule-day-card h5 {
    margin-bottom: 1rem;
    padding-bottom: 0.75rem;
    border-bottom: 2px solid rgba(40, 110, 180, 0.14);
  }

  .schedule-day-card table {
    width: 100%;
    border-collapse: separate;
    border-spacing: 0 0.65rem;
  }

  .schedule-day-card td {
    padding: 0.8rem 0.9rem;
    background: rgba(40, 110, 180, 0.05);
  }

  .schedule-day-card td:first-child {
    width: 38%;
    font-weight: 600;
    border-radius: 12px 0 0 12px;
  }

  .schedule-day-card td:last-child {
    border-radius: 0 12px 12px 0;
  }

  .plenary-speaker {
    margin: -0.25rem 0 1rem;
    font-size: 1.08rem;
    line-height: 1.4;
  }

  .plenary-speaker strong {
    font-size: 1.18rem;
  }

  .plenary-resources {
    margin: -0.7rem 0 1rem;
    font-size: 0.95rem;
  }

  .plenary-resources span {
    margin: 0 0.35rem;
    color: var(--global-text-color-light);
  }

  .paper-title {
    font-weight: 700;
  }

  .paper-authors {
    color: var(--global-text-color-light);
    font-size: 0.95rem;
  }

  @media (max-width: 900px) {
    .schedule-day-cards {
      grid-template-columns: 1fr;
    }
  }
</style>

### Program At A Glance

Below is the conference schedule at a glance. Details about the plenary talks, oral sessions, and poster session are provided after the overview.

{% capture schedule_at_a_glance_table %}
  <div class="schedule-table-wrap">
    <table class="schedule-table">
      <thead>
        <tr>
          <th class="title-heading" colspan="6">GSP 2026 Schedule</th>
        </tr>
        <tr>
          <th class="day-heading" colspan="2">Day 1 - Monday, June 8</th>
          <th class="day-heading" colspan="2">Day 2 - Tuesday, June 9</th>
          <th class="day-heading" colspan="2">Day 3 - Wednesday, June 10</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td class="time-slot">09:00-09:20</td>
          <td class="activity-cell">Welcome Message</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">09:20-10:20</td>
          <td class="activity-cell">Plenary Paolo Di Lorenzo</td>
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Gonzalo Mateos</td>
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Luana Ruiz</td>
        </tr>
        <tr>
          <td class="time-slot">10:20-11:20</td>
          <td class="activity-cell">Oral Session Mon-1</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Tue-1</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Wed-1</td>
        </tr>
        <tr>
          <td class="time-slot">11:20-11:50</td>
          <td class="activity-cell">Coffee Break</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">Coffee Break BBVA</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">Coffee Break</td>
        </tr>
        <tr>
          <td class="time-slot">11:50-13:30</td>
          <td class="activity-cell">Oral Session Mon-2</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Poster Session</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Oral Session Wed-2</td>
        </tr>
        <tr>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
        </tr>
        <tr>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Antonio Ortega</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Daniel Palomar</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Oral Session Wed-3</td>
        </tr>
        <tr>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Mon-3</td>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Tue-2</td>
          <td class="time-slot">16:00-16:20</td>
          <td class="activity-cell">Closing Ceremony</td>
        </tr>
        <tr>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break</td>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break BBVA</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Mon-4</td>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Tue-3</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr class="spacer-row">
          <td></td><td></td><td></td><td></td><td></td><td></td>
        </tr>
        <tr>
          <td class="time-slot">20:30-22:30</td>
          <td class="activity-cell">Welcome Reception (Casa Suecia)</td>
          <td class="time-slot">21:00-23:00</td>
          <td class="activity-cell">Banquet (Caf&eacute; Comercial)</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
      </tbody>
    </table>
  </div>
{% endcapture %}

<div class="schedule-preview schedule-detailed schedule-aesthetic-test schedule-light-default">
{{ schedule_at_a_glance_table }}
</div>

<div class="schedule-preview schedule-detailed schedule-aesthetic-test schedule-dark-mode">
{{ schedule_at_a_glance_table }}
</div>

---

### General Information

Lectures in the oral sessions are 20 minutes long, including Q&As. We recommend authors to aim for a 15-minute presentation leaving a few minutos for questions and switching the speaker. Posters should use A0 size in portrait orientation.

There will be two social events during the conference:

- Welcome Reception: Monday, June 8, 20:30-22:30, [Casa Suecia](https://www.google.com/maps/search/?api=1&query=Casa%20Suecia%20Madrid), Calle del Marqu&eacute;s de Casa Riera, 4, 28014 Madrid.
- Conference Banquet: Tuesday, June 9, 21:00-23:00, [Caf&eacute; Comercial](https://www.google.com/maps/search/?api=1&query=Caf%C3%A9%20Comercial%20Madrid), Glorieta de Bilbao, 7, 28004 Madrid.

---

### Plenary Talks

<p id="Paolo Di Lorenzo"></p>

#### Plenary Monday 9:20 - 10:20
<p class="plenary-speaker"><a href="https://research.uniroma1.it/researcher/161f6cb8ac97b460a616a4bc0ebe857b1ad100650298fee7e3ceb7f9"><strong>Paolo Di Lorenzo</strong></a>, Sapienza University of Rome</p>
<p class="plenary-resources"><a href="https://tv.urjc.es/video/6a27bdb38608dd59a7006f74" target="_blank" rel="noopener">Video</a><span aria-hidden="true">&middot;</span><a href="{{ '/assets/slides2026/plenaries/PaoloDiLorenzo.pdf' | relative_url }}" target="_blank">Slides</a></p>

**Title**: Sheaf-theoretic Signal Processing and Learning

**Abstract**: Classical graph signal processing (GSP) provides a powerful framework for modeling data on networks, but it is inherently limited to homogeneous signal spaces and pairwise interactions. Many modern applications, ranging from biological and social networks to distributed AI, require handling heterogeneous data and structured relationships beyond these assumptions. In this talk, we present sheaf-theoretic signal processing as a principled extension of GSP for modeling heterogeneous signals and complex interactions. By assigning vector spaces to nodes and edges, together with linear restriction maps, cellular sheaves encode geometric, semantic, and topological structure directly on graphs. This framework generalizes key GSP tools, leading to the sheaf Laplacian and the Sheaf Fourier Transform, whose spectrum captures signal inconsistency across the network. We then address the problem of learning sheaves from data, proposing scalable methods based on total variation minimization that jointly infer graph topology and inter-node alignment via efficient edge-wise and Procrustes-type solutions. We also show that connection graphs arise as a structured class of sheaves with a highly interpretable spectral characterization. Finally, we highlight applications in semantic communications and federated representation learning, where sheaf-based models enable alignment of heterogeneous latent spaces without enforcing a shared global representation, yielding improved performance in distributed settings.

<p id="Antonio Ortega"></p>

#### Plenary Monday 15:00 - 16:00
<p class="plenary-speaker"><a href="https://viterbi.usc.edu/directory/faculty/Ortega/Antonio"><strong>Antonio Ortega</strong></a>, University of Southern California</p>
<p class="plenary-resources"><a href="https://tv.urjc.es/video/6a2821d9dc45b9286e0f3e37" target="_blank" rel="noopener">Video</a><span aria-hidden="true">&middot;</span><a href="{{ '/assets/slides2026/plenaries/AntonioOrtega-Fast_GFTs.pdf' | relative_url }}" target="_blank">Slides</a></p>

**Title**: How to design fast GFTs

**Abstract**: In this talk, we provide an overview of recent advances for speeding up the computation of the Graph Fourier Transform (GFT). We first describe divide-and-conquer techniques that leverage graph structure, such as graph symmetries or graph decompositions via low-rank updates. For graphs whose structure does not yield sufficient speed-up in transform computation, we describe approximation methods, including direct transform approximations (via Givens rotations) and indirect methods that exploit more favorable structures (e.g., spectral sparsification). We demonstrate the advantages of these techniques in image/video coding and graph machine learning applications.<br><br>*Joint work with Samuel Fernández Menduiña, Keng-Shi Lu, Darukeesan Pakiyarajah, and Eduardo Pavez.*

<p id="Gonzalo Mateos"></p>

#### Plenary Tuesday 9:00 - 10:00
<p class="plenary-speaker"><a href="https://www.hajim.rochester.edu/ece/people/faculty/mateos_gonzalo/index.html"><strong>Gonzalo Mateos</strong></a>, University of Rochester</p>
<p class="plenary-resources"><a href="https://tv.urjc.es/video/6a290d7a16c7384cc2034ad4" target="_blank" rel="noopener">Video</a><span aria-hidden="true">&middot;</span><a href="{{ '/assets/slides2026/plenaries/GonzaloMateos-CoLiDE_slides.pdf' | relative_url }}" target="_blank">Slides</a></p>

**Title**: Concomitant Linear DAG Estimation

**Abstract**: We deal with the combinatorial problem of learning directed acyclic graph (DAG) structure from observational data adhering to a linear structural equation model (SEM). Leveraging advances in differentiable, nonconvex characterizations of acyclicity, recent efforts have advocated a continuous constrained optimization paradigm to efficiently explore the space of DAGs. Most existing methods employ lasso-type score functions to guide this search, which (i) require expensive penalty parameter retuning when the SEM noise variances change across problem instances; and (ii) implicitly rely on limiting homoscedasticity assumptions. In this talk, I will propose a new convex score function for sparsity-aware learning of linear DAGs, which incorporates concomitant estimation of scale and thus effectively decouples the sparsity parameter from noise levels. Regularization via a smooth, nonconvex acyclicity penalty term yields CoLiDE (Concomitant Linear DAG Estimation), a regression-based criterion amenable to efficient gradient computation and closed-form estimation of exogenous noise levels in heteroscedastic scenarios. The algorithm outperforms state-of-the-art methods without incurring added complexity, especially when the DAGs are larger, and the noise level profile is heterogeneous. CoLiDE exhibits enhanced stability manifested via reduced standard deviations in several domain-specific metrics, underscoring the robustness of the novel linear DAG estimator.

<p id="Daniel P. Palomar"></p>

#### Plenary Tuesday 15:00 - 16:00
<p class="plenary-speaker"><a href="https://seng.hkust.edu.hk/about/people/faculty/daniel-p-palomar"><strong>Daniel P. Palomar</strong></a>, The Hong Kong University of Science and Technology</p>
<p class="plenary-resources"><a href="https://tv.urjc.es/video/6a290fd6922c6523ab0717ff" target="_blank" rel="noopener">Video</a><span aria-hidden="true">&middot;</span><a href="{{ '/assets/slides2026/plenaries/DanielPalomar-slides-keynote-palomar-GSPW2026.pdf' | relative_url }}" target="_blank">Slides</a></p>

**Title**: Graphs in Financial Markets

**Abstract**: Financial markets generate high-dimensional, non-Gaussian, and time-varying data that challenge classical statistical models. Graph-based representations offer a principled way to capture the dependency structure among assets. This talk surveys recent advances in learning graphs from financial data, with emphasis on three settings: (i) the Polynomial Graphical Lasso, which jointly estimates the precision matrix and graph topology by exploiting graph stationarity; (ii) heavy-tailed and structured graph learning, where a Student-t model and spectral Laplacian constraints yield robust k-component and bipartite graphs that reflect market sector structure; and (iii) time-varying graph learning, which combines a non-negative VAR(1) temporal prior with heavy-tailed likelihoods to track market dynamics, detect crises, and improve portfolio performance.

<p id="Luana Ruiz"></p>

#### Plenary Wednesday 9:00 - 10:00
<p class="plenary-speaker"><a href="https://engineering.jhu.edu/ams/faculty/luana-ruiz/"><strong>Luana Ruiz</strong></a>, Johns Hopkins University</p>
<p class="plenary-resources"><a href="https://tv.urjc.es/video/6a29b8ce617f19f93e0c8398" target="_blank" rel="noopener">Video</a><span aria-hidden="true">&middot;</span><a href="{{ '/assets/slides2026/plenaries/LuanaRuiz-distance-preserving-gml-GSPW-2026.pdf' | relative_url }}" target="_blank">Slides</a></p>

**Title**: Distance-Preserving Graph Machine Learning

**Abstract**: A central challenge in graph machine learning is that standard learning-based methods capture local connectivity while distorting or ignoring the metric structure of graphs at larger scales. In this talk, I will present two lines of work that address this challenge from complementary angles. The first studies landmark-based distance-preserving embeddings on inhomogeneous random graphs, a flexible model capturing the community structure and degree variability observed in real networks. By analyzing neighborhood expansion via multi-type branching process approximations, we show that the embedding dimension required to achieve near-exact shortest-path preservation is significantly smaller than worst-case theory predicts, with the improvement governed by the graph's connectivity structure. We further show that GNN-based approximations of landmark distances transfer effectively from small synthetic graphs to large real-world networks, offering a scalable surrogate for exact shortest-path computation. The second line of work introduces a mesoscopic graph rewiring strategy based on opinion dynamics-inspired contagion processes. By promoting node pairs with strong multi-hop reinforcement to direct neighbors, the method constructs a sparse auxiliary graph that provably improves homophily and whose edge weights reflect a bounded effective resistance. Applied to both GNNs and graph transformers, cascade rewiring yields consistent accuracy gains across benchmarks. Together, these results suggest a unified perspective on graph machine learning grounded in the preservation and exploitation of metric structure across scales.

---

### Oral Sessions

#### Oral Session Mon-1 (Monday 10:20 - 11:20) - Joint Time-Vertex GSP
+ <span class="paper-title">Subspace Projection Methods for Fast Spectral Embeddings of Evolving Graphs.</span><br><span class="paper-authors">Mohammad Eini (Michigan State University); Abdullah Karaaslanli (Michigan State University); Vassilis Kalantzis (IBM Research); Panagiotis Traganitis (Michigan State University).</span>
+ <span class="paper-title">Locally Stationary Time-Vertex Process Models.</span><br><span class="paper-authors">Deniz Aslan (Middle East Technical University); Elif Vural (Middle East Technical University).</span>
+ <span class="paper-title">Conformal Inference for Graphs.</span><br><span class="paper-authors">Sundeep Prabhakar Chepuri (Indian Institute of Science, Bangalore); Sonakshi Dua (Indian Institute of Science, Bangalore); Gonzalo Mateos (University of Rochester).</span>

#### Oral Session Mon-2 (Monday 11:50 - 13:30) - GSP Theory
+ <span class="paper-title">Möbius Model for Graph Signal Processing on Weighted DAGs.</span><br><span class="paper-authors">Vedran Mihal (ETH Zurich); Markus Püschel (ETH Zurich).</span>
+ <span class="paper-title">Graph-Aware Diffusion for Signal Generation.</span><br><span class="paper-authors">Vimal Kumarasamy Balasubramanian (TU Delft); Sergio Rozada (URJC); Antonio G. Marques (URJC); Elvin Isufi (TU Delft); Hadi Jamali Rad (TU Delft); Andrea Cavallo (TU Delft).</span>
+ <span class="paper-title">Learning Dirac Spectral Transforms for Topological Signals.</span><br><span class="paper-authors">Leonardo Di Nino (Sapienza, Università di Roma); Tiziana Cattai (Sapienza, Università di Roma); Sergio Barbarossa (Sapienza, Università di Roma); Ginestra Bianconi (School of Mathematical Sciences, Queen Mary University of London, UK); Paolo Di Lorenzo (Sapienza, Università di Roma).</span>
+ <span class="paper-title">Sampling in the Graph Signal Processing Companion Model.</span><br><span class="paper-authors">John Shi (Carnegie Mellon University); Jose Moura (Carnegie Mellon University).</span>
+ <span class="paper-title">Optimal Wiener-Filter Solutions for Denoising of Graph Signals on Directed Graphs.</span><br><span class="paper-authors">Chun Hei Michael Chan (EPFL); Alexandre Cionca (EPFL); Dimitri Van De Ville (EPFL).</span>

#### Oral Session Mon-3 (Monday 16:00 - 17:00) - Higher Order SP & Topological SP I
+ <span class="paper-title">Don’t be Afraid of Cell Complexes! An Introduction to Cell Complexes and Topological Signal Processing from an Applied Perspective.</span><br><span class="paper-authors">Josef Hoppe (RWTH Aachen University); Vincent P. Grande (RWTH Aachen University); Michael T. Schaub (RWTH Aachen University).</span>
+ <span class="paper-title">Scalable Higher-Order Topology Identification from Nodal Observations.</span><br><span class="paper-authors">Geert Leus (TU Delft); Elvin Isufi (TU Delft).</span>
+ <span class="paper-title">Stationarity and Spectral Characterization of Random Signals on Simplicial Complexes.</span><br><span class="paper-authors">Madeline Navarro (Rice University); Andrei Buciulea Vlas (Universidad Rey Juan Carlos); Santiago Segarra (Rice University); Antonio G. Marques (Universidad Rey Juan Carlos).</span>

#### Oral Session Mon-4 (Monday 17:30 - 18:30) - Higher Order SP & Topological SP II
+ <span class="paper-title">Vertex-frequency Hypergraph Signal Processing: Analytic Tools and Applications.</span><br><span class="paper-authors">Alcebiades Dal Col (Federal University of Espirito Santo); Fabiano Petronetto (Federal University of Espirito Santo); José R. de Oliveira Neto (Federal University of Pernambuco); Juliano B. Lima (Federal University of Pernambuco).</span>
+ <span class="paper-title">Framework for Directed Hypergraph Signal Processing via tensor t-SVD.</span><br><span class="paper-authors">Carlos Mundo Levano (University of Delaware); Nicolas Bello (University of Delaware); Dan Lau (University of Kentucky); Gonzalo Arce (University of Delaware).</span>
+ <span class="paper-title">Processing Probabilistic Signals on Causal Abstraction Networks.</span><br><span class="paper-authors">Gabriele D'Acunto (Sapienza University); Paolo Di Lorenzo (Sapienza University); Sergio Barbarossa (Sapienza University).</span>

#### Oral Session Tue-1 (Tuesday 10:00 - 11:00) - Non-Linear GSP
+ <span class="paper-title">Nonstationary Graph Filters Based on Localized Frames.</span><br><span class="paper-authors">Philipp Reingruber (TU Wien); Gerald Matz (TU Wien).</span>
+ <span class="paper-title">Covariance Scattering Transforms.</span><br><span class="paper-authors">Andrea Cavallo (Delft University of Technology); Ayushman Raghuvanshi (Indian Institute of Science); Sundeep Prabhakar Chepuri (Indian Institute of Science); Elvin Isufi (Delft University of Technology).</span>
+ <span class="paper-title">Sample entropy for graph signals: An approach to nonlinear analysis of graph signals.</span><br><span class="paper-authors">Mei san lei (University of Edinburgh); John Stewart Fabila-Carrasco (University of Cardiff); Javier Escudero (University of Edinburgh).</span>

#### Oral Session Tue-2 (Tuesday 16:00 - 17:00) - Geometric Deep Learning I
+ <span class="paper-title">Unrolling Dynamic Programming via Graph Filters.</span><br><span class="paper-authors">Sergio Rozada (URJC); Samuel Rey (URJC); Gonzalo Mateos (University of Rochester); Antonio G. Marques (URJC).</span>
+ <span class="paper-title">Advection–Diffusion on Graphs: A Bakry–Émery Laplacian for Spectral Graph Neural Networks.</span><br><span class="paper-authors">Mia Zosso (EPFL); Pierre Vandergheynst (EPFL); Victor Kawasaki-Borruat (EPFL); Ali Hariri (EPFL); Pierre-Gabriel Berlureau (ENS).</span>
+ <span class="paper-title">Adaptive Node Feature Selection for Graph Neural Networks.</span><br><span class="paper-authors">Ali Azizpour (Rice University); Madeline Navarro (Rice University); Santiago Segarra (Rice University).</span>

#### Oral Session Tue-3 (Tuesday 17:30 - 18:30) - Higher Order SP & Topological SP III
+ <span class="paper-title">Joint Simplicial Complex Learning via Binary Linear Programming.</span><br><span class="paper-authors">Varun Sarathchandran (Delft University of Technology); Geert Leus (Delft University of Technology).</span>
+ <span class="paper-title">Cross-Laplacians Based Topological Signal Processing over Cell MultiComplexes.</span><br><span class="paper-authors">Stefania Sardellitti (University Mercatorum); Breno C. Bispo (Federal University of Pernambuco); Fernando A. N. Santos (University of Amsterdam); Juliano B. Lima (Federal University of Pernambuco).</span>
+ <span class="paper-title">Hodge-Aware Surrogates for Testing Stationarity in Topological Signals.</span><br><span class="paper-authors">Flavia Petruso (EPFL); Chun Hei Michael Chan (EPFL); Dimitri Van De Ville (EPFL).</span>

#### Oral Session Wed-1 (Wednesday 10:00 - 11:00) - Graph Learning
+ <span class="paper-title">A Covariance Matching Approach to Graph Topology Identification.</span><br><span class="paper-authors">Yongsheng Han (TU Delft); Geert Leus (TU Delft); Raj Rajan (TU Delft).</span>
+ <span class="paper-title">BUILD with precision: Bottom-up inference of linear DAGs.</span><br><span class="paper-authors">Hamed Ajorlou (University of Rochester); Samuel Rey (King Juan Carlos University); Gonzalo Mateos (University of Rochester); Geert Leus (TU Delft); Antonio G. Marques (King Juan Carlos University).</span>
+ <span class="paper-title">Sparsity-Aware Extended Kalman Filter for Tracking Dynamic Graphs.</span><br><span class="paper-authors">Lital Dabush (Ben-Gurion University); Nir Shlezinger (Ben-Gurion University); Tirza Routtenberg (Ben-Gurion University).</span>

#### Oral Session Wed-2 (Wednesday 11:30 - 13:30) - Geometric Deep Learning II
+ <span class="paper-title">Fixed Aggregation Features Can Rival GNNs.</span><br><span class="paper-authors">Celia Rubio-Madrigal (CISPA Helmholtz Center for Information Security); Rebekka Burkholz (CISPA Helmholtz Center for Information Security).</span>
+ <span class="paper-title">Size Transferability of Graph Transformers with Convolutional Positional Encodings.</span><br><span class="paper-authors">Javier Porras Valenzuela (University of Pennsylvania); Zhiyang Wang (University of California San Diego); Xiaotao Shang (University of Pennsylvania); Yusu Wang (University of California San Diego); Alejandro Ribeiro (University of Pennsylvania).</span>
+ <span class="paper-title">A Graph Attention Network Approach to Super-Resolution Spatial Transcriptomic Data.</span><br><span class="paper-authors">Luis Alonso (University of Navarra); Mikel Hernaez (University of Navarra); Idoia Ochoa (University of Navarra).</span>
+ <span class="paper-title">L2G-Net: Local to Global Spectral Graph Neural Networks via Cauchy Factorizations.</span><br><span class="paper-authors">Samuel Fernandez (University of Southern California); Eduardo Pavez (University of Southern California); Antonio Ortega (University of Southern California).</span>
+ <span class="paper-title">Graph Signal Diffusion Models for Wireless Resource Allocation.</span><br><span class="paper-authors">Yigit Berkay Uslu (University of Pennsylvania); Samar Hadou (University of Pennsylvania); Shirin Saeedi Bidokhti (University of Pennsylvania); Alejandro Ribeiro (University of Pennsylvania).</span>
+ <span class="paper-title">On the Effectiveness of Pretraining for Graph Combinatorial Optimization.</span><br><span class="paper-authors">David Aguado (Universidad Politécnica de Madrid); Daniel Fuertes (Universidad Politécnica de Madrid); Carlos R. del-Blanco (Universidad Politécnica de Madrid); Fernando Jaureguizar (Universidad Politécnica de Madrid).</span>

#### Oral Session Wed-3 (Wednesday 15:00 - 16:00) - Higher Order SP & Topological SP IV
+ <span class="paper-title">STORM: Simplicial Topological Recurrent Model for Dynamics on Higher-Order Domains.</span><br><span class="paper-authors">Mohamed Salah Jebali (TU Delft); Claudio Battiloro (Harvard); Elvin Isufi (TU Delft).</span>
+ <span class="paper-title">A Graph-Structured VAR Model for Data with Higher Order Temporal Dependencies and Heavy Tails.</span><br><span class="paper-authors">Amirhossein Javaheri (KTH Royal Institute of Technology); Saikat Chatterjee (KTH Royal Institute of Technology); Daniel Palomar (Hong Kong University of Science and Technology).</span>
+ <span class="paper-title">A Framework for Directed Acyclic Hypergraph Learning.</span><br><span class="paper-authors">Zhiyuan Dong (University of Delaware); Carlos Mundo-Levano (University of Delaware); Gonzalo R. Arce (University of Delaware); Wei Qian (University of Delaware); Daniel Lau (University of Kentucky).</span>

---

### Poster Session

#### Poster Session (Tuesday 11:30 - 13:30)
+ <span class="paper-title">Causality-driven Disentangled Representation Learning in Multiplex Graphs.</span><br><span class="paper-authors">Saba Nasiri, Selin Aviyente (Michigan State University), Dorina Thanou (EPFL).</span>
+ <span class="paper-title">Topological Kalman Filtering on Cell Complexes.</span><br><span class="paper-authors">Chengen Liu (Delft University of Technology).</span>
+ <span class="paper-title">Learning Graph Topology with Functional Priors: A Graph Formation Model Perspective.</span><br><span class="paper-authors">Chenyue Zhang (Chinese University of Hong Kong); Shangyuan Liu (Chinese University of Hong Kong); Hoi-To Wai (Chinese University of Hong Kong); Anthony Man-Cho So (Chinese University of Hong Kong).</span>
+ <span class="paper-title">GNNs Getting ComFy: Community and Feature Similarity Guided Rewiring.</span><br><span class="paper-authors">Celia Rubio-Madrigal (CISPA Helmholtz Center for Information Security); Adarsh Jamadandi (IRISA, University of Rennes); Rebekka Burkholz (CISPA Helmholtz Center for Information Security).</span>
+ <span class="paper-title">Distance-Misaligned Training in Graph Transformers and Adaptive Graph-Aware Control.</span><br><span class="paper-authors">Qinhan Hou (University of Helsinki); Jing Tang (University of Helsinki).</span>
+ <span class="paper-title">Data-Driven Higher-Order Topology Learning for Leak Detection in Dynamic Water Distribution Networks.</span><br><span class="paper-authors">Tiziana Cattai (Sapienza University of Rome); Stefania Sardellitti (Universitas Mercatorum); Stefania Colonnese (Sapienza University of Rome); Francesca Cuomo (Sapienza University of Rome); Sergio Barbarossa (Sapienza University of Rome).</span>
+ <span class="paper-title">ADAPTIVEMIXGNN: Local Adaptive Inductive Bias for Heterophilic Node Classification.</span><br><span class="paper-authors">Miguel Alcocer (King Juan Carlos University, Madrid); Javier Muñoz (King Juan Carlos University, Madrid); Álvaro Morán (King Juan Carlos University, Madrid).</span>
+ <span class="paper-title">Planar Horizontal Visibility Graphs for Chromatin Dynamics Analysis: Applications to Cellular Metabolic States.</span><br><span class="paper-authors">Lucía Benito (Universidad Francisco de Vitoria); Diego Herráez (Universidad Francisco de Vitoria).</span>
+ <span class="paper-title">A Sheaf-Theoretic Framework for Distributed Multi-Site Channel Charting.</span><br><span class="paper-authors">Enrico Grimaldi (Sapienza University of Rome); Leonardo Di Nino (Sapienza University of Rome); Mario Edoardo Pandolfo (Sapienza University of Rome); Gabriele D'Acunto (Sapienza University of Rome); Sergio Barbarossa (Sapienza University of Rome); Paolo Di Lorenzo (Sapienza University of Rome).</span>
+ <span class="paper-title">Shattering the Speed-Accuracy Dichotomy in Asymmetric Routing via Anisotropic GNNs.</span><br><span class="paper-authors">Gonzalo Mantiñán Suárez (Universidad Politécnica de Madrid); Daniel Fuertes (Universidad Politécnica de Madrid); Carlos R. del-Blanco (Universidad Politécnica de Madrid); Fernando Jaureguizar (Universidad Politécnica de Madrid).</span>
+ <span class="paper-title">Precision Neural Networks: Joint Graph and Relational Learning.</span><br><span class="paper-authors">Andrea Cavallo (Delft University of Technology); Samuel Rey (King Juan Carlos University); Antonio G. Marques (King Juan Carlos University); Elvin Isufi (Delft University of Technology).</span>
+ <span class="paper-title">Learning Dynamics in Streaming Weighted Higher-Order Networks.</span><br><span class="paper-authors">Rohan Thekkemarickal Money (Simula); Baltasar Beferull-Lozano (Simula Metropolitan Center for Digital Engineering); Elvin Isufi (TU Delft).</span>
+ <span class="paper-title">Enhancing Transformer-based Routing by Encoding Distance via Relative Positional Encoding.</span><br><span class="paper-authors">Leyre Encío (Universidad Politécnica de Madrid); Daniel Fuertes (Universidad Politécnica de Madrid); Carlos R. del-Blanco (Universidad Politécnica de Madrid); Fernando Jaureguizar (Universidad Politécnica de Madrid).</span>
+ <span class="paper-title">Random Spectral Features for Graph Kernel Machines.</span><br><span class="paper-authors">Valentin de Bassompierre (UCLouvain); Laurent Jacques (UCLouvain); Jean-Charles Delvenne (UCLouvain).</span>

<!--
<div class="schedule-preview">
  <div class="schedule-note">Three separate day cards with roomy time slots, especially friendly on mobile.</div>
  <div class="schedule-day-cards">
    <div class="schedule-day-card">
      <h5>Monday, June 8</h5>
      <table>
        <tbody>
          <tr><td>09:00-10:00</td><td>Plenary</td></tr>
          <tr><td>10:00-13:00</td><td>Technical Sessions</td></tr>
          <tr><td>13:00-15:00</td><td>Lunch</td></tr>
          <tr><td>15:00-16:00</td><td>Plenary</td></tr>
          <tr><td>16:00-18:00</td><td>Technical Sessions</td></tr>
        </tbody>
      </table>
    </div>
    <div class="schedule-day-card">
      <h5>Tuesday, June 9</h5>
      <table>
        <tbody>
          <tr><td>09:00-10:00</td><td>Plenary</td></tr>
          <tr><td>10:00-13:00</td><td>Technical Sessions</td></tr>
          <tr><td>13:00-15:00</td><td>Lunch</td></tr>
          <tr><td>15:00-16:00</td><td>Plenary</td></tr>
          <tr><td>16:00-18:00</td><td>Technical Sessions</td></tr>
        </tbody>
      </table>
    </div>
    <div class="schedule-day-card">
      <h5>Wednesday, June 10</h5>
      <table>
        <tbody>
          <tr><td>09:00-10:00</td><td>Plenary</td></tr>
          <tr><td>10:00-13:00</td><td>Technical Sessions</td></tr>
          <tr><td>13:00-15:00</td><td>Lunch</td></tr>
          <tr><td>15:00-16:00</td><td>Plenary</td></tr>
          <tr><td>16:00-18:00</td><td>Technical Sessions</td></tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
-->
