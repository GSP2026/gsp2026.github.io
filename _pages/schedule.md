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

### Program Schedule

Two versions of the GSP 2026 schedule are shown below for comparison while the final layout is refined.

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

  .schedule-aesthetic-test .spacer-row td {
    height: 2.2rem;
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

  @media (max-width: 900px) {
    .schedule-day-cards {
      grid-template-columns: 1fr;
    }
  }
</style>

### Program At A Glance

The detailed technical program below was extracted from the GSPTechnicalProgram2026 document. Two table treatments are provided for comparison.

#### Current Compact Version

<div class="schedule-preview schedule-detailed">
  <div class="schedule-note">Detailed technical program (three-day view).</div>
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
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Gonzalo Mateos</td>
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Luana Ruiz</td>
        </tr>
        <tr>
          <td class="time-slot">09:20-10:20</td>
          <td class="activity-cell">Plenary Paolo Di Lorenzo</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Tue-1</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Wed-1</td>
        </tr>
        <tr>
          <td class="time-slot">10:20-11:20</td>
          <td class="activity-cell">Oral Session Mon-1</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">BBVA Coffee Break 2A</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">Coffee Break A</td>
        </tr>
        <tr>
          <td class="time-slot">11:20-11:50</td>
          <td class="activity-cell">Coffee Break A</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Poster Session</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Oral Session Wed-2</td>
        </tr>
        <tr>
          <td class="time-slot">11:50-13:30</td>
          <td class="activity-cell">Oral Session Mon-2</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
        </tr>
        <tr>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Daniel Palomar</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Oral Session Wed-3</td>
        </tr>
        <tr>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Antonio Ortega</td>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Tue-2</td>
          <td class="time-slot"></td>
          <td class="activity-cell">Closing Ceremony</td>
        </tr>
        <tr>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Mon-3</td>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break 2B</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break B</td>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Tue-3</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Mon-4</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
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
</div>

#### Visual Test Version

<div class="schedule-preview schedule-detailed schedule-aesthetic-test">
  <div class="schedule-note">A smaller 8pt version with separators only between days.</div>
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
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Gonzalo Mateos</td>
          <td class="time-slot">09:00-10:00</td>
          <td class="activity-cell">Plenary Luana Ruiz</td>
        </tr>
        <tr>
          <td class="time-slot">09:20-10:20</td>
          <td class="activity-cell">Plenary Paolo Di Lorenzo</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Tue-1</td>
          <td class="time-slot">10:00-11:00</td>
          <td class="activity-cell">Oral Session Wed-1</td>
        </tr>
        <tr>
          <td class="time-slot">10:20-11:20</td>
          <td class="activity-cell">Oral Session Mon-1</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">BBVA Coffee Break 2A</td>
          <td class="time-slot">11:00-11:30</td>
          <td class="activity-cell">Coffee Break A</td>
        </tr>
        <tr>
          <td class="time-slot">11:20-11:50</td>
          <td class="activity-cell">Coffee Break A</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Poster Session</td>
          <td class="time-slot">11:30-13:30</td>
          <td class="activity-cell">Oral Session Wed-2</td>
        </tr>
        <tr>
          <td class="time-slot">11:50-13:30</td>
          <td class="activity-cell">Oral Session Mon-2</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
        </tr>
        <tr>
          <td class="time-slot">13:30-15:00</td>
          <td class="activity-cell">Lunch Break</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Daniel Palomar</td>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Oral Session Wed-3</td>
        </tr>
        <tr>
          <td class="time-slot">15:00-16:00</td>
          <td class="activity-cell">Plenary Antonio Ortega</td>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Tue-2</td>
          <td class="time-slot"></td>
          <td class="activity-cell">Closing Ceremony</td>
        </tr>
        <tr>
          <td class="time-slot">16:00-17:00</td>
          <td class="activity-cell">Oral Session Mon-3</td>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break 2B</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">17:00-17:30</td>
          <td class="activity-cell">Coffee Break B</td>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Tue-3</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
        </tr>
        <tr>
          <td class="time-slot">17:30-18:30</td>
          <td class="activity-cell">Oral Session Mon-4</td>
          <td class="time-slot"></td>
          <td class="activity-cell"></td>
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
</div>

#### Plenary Talks

<p id="Gonzalo Mateos"></p>

##### **Gonzalo Mateos**

**Title**: Concomitant Linear DAG Estimation

**Abstract**: We deal with the combinatorial problem of learning directed acyclic graph (DAG) structure from observational data adhering to a linear structural equation model (SEM). Leveraging advances in differentiable, nonconvex characterizations of acyclicity, recent efforts have advocated a continuous constrained optimization paradigm to efficiently explore the space of DAGs. Most existing methods employ lasso-type score functions to guide this search, which (i) require expensive penalty parameter retuning when the SEM noise variances change across problem instances; and (ii) implicitly rely on limiting homoscedasticity assumptions. In this talk, I will propose a new convex score function for sparsity-aware learning of linear DAGs, which incorporates concomitant estimation of scale and thus effectively decouples the sparsity parameter from noise levels. Regularization via a smooth, nonconvex acyclicity penalty term yields CoLiDE (Concomitant Linear DAG Estimation), a regression-based criterion amenable to efficient gradient computation and closed-form estimation of exogenous noise levels in heteroscedastic scenarios. The algorithm outperforms state-of-the-art methods without incurring added complexity, especially when the DAGs are larger, and the noise level profile is heterogeneous. CoLiDE exhibits enhanced stability manifested via reduced standard deviations in several domain-specific metrics, underscoring the robustness of the novel linear DAG estimator.

<p id="Daniel P. Palomar"></p>

##### **Daniel P. Palomar**

**Title**: Graphs in Financial Markets

**Abstract**: Financial markets generate high-dimensional, non-Gaussian, and time-varying data that challenge classical statistical models. Graph-based representations offer a principled way to capture the dependency structure among assets. This talk surveys recent advances in learning graphs from financial data, with emphasis on three settings: (i) the Polynomial Graphical Lasso, which jointly estimates the precision matrix and graph topology by exploiting graph stationarity; (ii) heavy-tailed and structured graph learning, where a Student-t model and spectral Laplacian constraints yield robust k-component and bipartite graphs that reflect market sector structure; and (iii) time-varying graph learning, which combines a non-negative VAR(1) temporal prior with heavy-tailed likelihoods to track market dynamics, detect crises, and improve portfolio performance.

<p id="Luana Ruiz"></p>

##### **Luana Ruiz**

**Title**: Distance-Preserving Graph Machine Learning

**Abstract**: A central challenge in graph machine learning is that standard learning-based methods capture local connectivity while distorting or ignoring the metric structure of graphs at larger scales. In this talk, I will present two lines of work that address this challenge from complementary angles. The first studies landmark-based distance-preserving embeddings on inhomogeneous random graphs, a flexible model capturing the community structure and degree variability observed in real networks. By analyzing neighborhood expansion via multi-type branching process approximations, we show that the embedding dimension required to achieve near-exact shortest-path preservation is significantly smaller than worst-case theory predicts, with the improvement governed by the graph's connectivity structure. We further show that GNN-based approximations of landmark distances transfer effectively from small synthetic graphs to large real-world networks, offering a scalable surrogate for exact shortest-path computation. The second line of work introduces a mesoscopic graph rewiring strategy based on opinion dynamics-inspired contagion processes. By promoting node pairs with strong multi-hop reinforcement to direct neighbors, the method constructs a sparse auxiliary graph that provably improves homophily and whose edge weights reflect a bounded effective resistance. Applied to both GNNs and graph transformers, cascade rewiring yields consistent accuracy gains across benchmarks. Together, these results suggest a unified perspective on graph machine learning grounded in the preservation and exploitation of metric structure across scales.

<p id="Paolo Di Lorenzo"></p>

##### **Paolo Di Lorenzo**

**Title**: Sheaf-theoretic Signal Processing and Learning

**Abstract**: Classical graph signal processing (GSP) provides a powerful framework for modeling data on networks, but it is inherently limited to homogeneous signal spaces and pairwise interactions. Many modern applications, ranging from biological and social networks to distributed AI, require handling heterogeneous data and structured relationships beyond these assumptions. In this talk, we present sheaf-theoretic signal processing as a principled extension of GSP for modeling heterogeneous signals and complex interactions. By assigning vector spaces to nodes and edges, together with linear restriction maps, cellular sheaves encode geometric, semantic, and topological structure directly on graphs. This framework generalizes key GSP tools, leading to the sheaf Laplacian and the Sheaf Fourier Transform, whose spectrum captures signal inconsistency across the network. We then address the problem of learning sheaves from data, proposing scalable methods based on total variation minimization that jointly infer graph topology and inter-node alignment via efficient edge-wise and Procrustes-type solutions. We also show that connection graphs arise as a structured class of sheaves with a highly interpretable spectral characterization. Finally, we highlight applications in semantic communications and federated representation learning, where sheaf-based models enable alignment of heterogeneous latent spaces without enforcing a shared global representation, yielding improved performance in distributed settings.

<p id="Antonio Ortega"></p>

##### **Antonio Ortega**

**Title**: How to design fast GFTs

**Abstract**: In this talk, we provide an overview of recent advances for speeding up the computation of the Graph Fourier Transform (GFT). We first describe divide-and-conquer techniques that leverage graph structure, such as graph symmetries or graph decompositions via low-rank updates. For graphs whose structure does not yield sufficient speed-up in transform computation, we describe approximation methods, including direct transform approximations (via Givens rotations) and indirect methods that exploit more favorable structures (e.g., spectral sparsification). We demonstrate the advantages of these techniques in image/video coding and graph machine learning applications.<br><br>*Joint work with Samuel Fernández Menduiña, Keng-Shi Lu, Darukeesan Pakiyarajah, and Eduardo Pavez.*


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
