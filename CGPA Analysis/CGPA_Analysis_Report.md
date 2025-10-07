### CGPA Analysis Report: Uncovering Drivers of Student Success

This report analyzes a dataset of student CGPAs (Cumulative Grade Point Average, a 0-10 scale measuring academic performance) alongside factors like internships, placements (job offers), and college IDs. The goal: Reveal patterns to guide recruitment, education strategies, and career advice. Data is aggregated from an interactive dashboard, showing sums and distributions for quick insights. Total CGPA sum across all students: 75,320—think of this as collective "grade points" for comparisons.

#### Executive Summary
- **Core Finding**: Internships boost placement rates, but strong grades alone secure jobs for many (32% of CGPA sum from non-interns who got placed).
- **Key Stats**: 81% of grade points from students without internships; 61% from unplaced students. Top colleges outperform, with CGPA peaks in 7-8 range.
- **Implication for Employers**: Prioritize high-CGPA candidates from leading colleges—internships signal initiative, but aren't mandatory for success.
- **Data Scope**: Aggregates from multiple colleges; no raw student count, but distributions suggest ~5,000-10,000 records based on bin counts.

This analysis demonstrates data visualization and interpretation skills using tools like Power BI/Tableau, turning raw metrics into actionable business insights.

#### 1. Overall CGPA Distribution
CGPA follows a bell curve: Most students score 6-8 (peak counts ~1,200 in 7-8 bin), tapering at extremes (under 100 in 4-5 or 10-11). 
- **Teaching Point**: This normal distribution teaches that average performance dominates—outliers (geniuses or strugglers) are rare. For employers, target the 7+ range for reliable hires.
- **Visual Insight**: Bar chart shows mid-ranges dominate, highlighting opportunities to uplift low performers via tutoring.

#### 2. Impact of Internships and Placements
- **Internship Breakdown**: No internship: 81.1% of total CGPA sum (61,077 points); Yes: 18.9% (14,243). Max sum for no internship: 45,560.
- **Placement Breakdown**: No placement: 60.5% (45,569); Yes: 39.5% (29,751). Max sum for no placement: 61,070.
- **Cross-Analysis (Pivot Table)**:

  | Internship | No Placement | Yes Placement | Total |
  |------------|--------------|---------------|-------|
  | No        | 49.0%       | 32.1%        | 81.1% |
  | Yes       | 11.5%       | 7.4%         | 18.9% |
  | **Total** | **60.5%**   | **39.5%**    | **100%** |

- **Teaching Point**: Read this as percentages of total grade points. Example: 32.1% from non-interns who landed jobs—proves grades can compensate for lack of experience. Interns are underrepresented but convert better to placements (7.4% vs. 11.5% unplaced).
- **Employer Tip**: Screen for internships to find proactive talent, but don't overlook high-CGPA non-interns—they form a large, capable pool.

#### 3. College Performance Highlights
- **Top/Bottom**: Max sum at CLG0062 (990 points); Min at CLG0042 (590). Top 10 (bar chart): Led by CLG0003 (~800), down to ~200 for 10th.
- **Bubble Chart**: Larger bubbles for higher CGPA sums per college—colors differentiate IDs, showing clustering around mid-performers.
- **Sankey Diagram**: Flows internship experience into college contributions, revealing how "No" internships dominate across schools.
- **Teaching Point**: Colleges vary due to resources or admissions—use this to benchmark. For example, top colleges contribute disproportionately, teaching economies of scale in education.
- **Employer Tip**: Recruit from top 10 (e.g., CLG0003-CLG0062) for higher average talent; analyze your hires against this to optimize campus visits.

#### Recommendations
- **For Students**: Build grades first (core to 32% placement success without internships), then add experience—it's a 39% placement edge.
- **For Educators**: Promote internships in underperforming colleges to close gaps; focus interventions on 4-6 CGPA range.
- **For Employers**: Use CGPA thresholds (7+) in screening; partner with top colleges for pipelines. Future analysis: Add student counts for per-capita averages via regression modeling.

This project showcases my ability to extract insights from dashboards, blending stats with strategy to drive decisions. Open to discussing how this applies to your team's needs.
