# Biohackathon-Team-16
# Task B: Selecting a disease to study - Cystic Fibrosis
Symptoms, diagnostic, and prognostic criteria:
  Symptoms: 
    - Respiratory: persistent coughing, recurrent lung infections, wheezing or shortness of breathh, and inflamed nasal passages or       sinusitis 
    - Digestive: greasy and bulky stools, poor weight gain and growth, severe constipation, and intestinal blockage- particulary in newborns
    - Miscellaneous: very salty skin, chronic fatigue, male infertility, and clubbing of fingers and toes.
  Diagnostic criteria: patients must meet the criteria in at least two categories
    - positive newborn screening
    - elevated sweat levels (>/= 60 mmol/L
    - abnormal nasal potiental difference measurements
    - consistent cystic fibrosis clinical symtpoms
    - identification of two disease causing mutations in cystic fibrosis.
  Prognostic criteria:
    - genotype: different CFTR mutations affect disease severity
    - age: the later it is, the worse it gets. treatment also becomes less effective.
    - lung function: forced expiratory volume in 1 second (FEV1) is a key predictor of survival. 
    - nutritional status: better nutrition correlates with improved lung function and survival. 
    - presence of complications: chronic infections that worsen prognosis.
    - access to specialized cystic fibrosis care.
Frontline treatments: 
- CFTR Modulator Therapies: primary one is Trifakta, it targets the CFTR gene to improve it, however, not all patients with cystic fibrosis have a faulty CFTR gene
- Airway Clearance Techniques: a multitude of different physical therapies used to breakup mucus in the lungs 
- Surgery: Nasal and Sinus surgery, bowel surgery, or full lung transplants

Criteria for a successful treatment:
- Improvements in CFTR function as measured by sweat chloride tests
- Reduction in the rate of lung function decline
- Improvements in pancreatic function in some cases

Options if frontline therapy fails:
- Anti-inflammatory treatments
- Nutritional support
- Clinical Trials
- Lung transplant (extreme)

Organs involved in the expression of cystic fibrosis:
- Epithelial cells are faulty which then affects the lungs and digestive system

# Task C: Finding a gene underlying cystic fibrosis
Genes associated with CF:
- Primary: CTFR
- Modifiers: EDRNA, ADIPOR2, IFRD1, MSRA, IL8, MBL2

When are these genes normally expressed in development:


What tissue are these genes expressed in:

When are these genes abnormally expressed in CF and in what tissue:
- there are multiple types of mutations of the CFTR gene: 

    Class I: Protein production mutations
    Class II: Protein processing mutations (e.g., F508del, the most common CF mutation)
    Class III: Gating mutations
    Class IV: Conductance mutations
    Class V: Insufficient protein mutations
    Class VI: Stability mutations


# Task D: Build a protein:protein interaction (PPI) network using the known gene protein product(s) as seeds.

What is the difference between a protein:protein interaction (PPI) network and a gene co-expression network?
- PPIs represent physical interactions between proteins and typically are based on experimental evidence. Edges in these networks represent physical contact or functional association between proteins. Gene co-expression networks represent similarities in gene expression patterns, often via microarray or RNA-seq data.

How do I find interacting proteins with a seed protein?  Use the EBI Intact database as an example.  Also note how one can access Intact via Cytoscape.
- Enter seed proteins in search box and filter as needed in EBI Intact.
- Within Cytoscape, download “IntAct Cytoscape”

How can I visualize and analyze the PPI network?  For example, how can I determine if the network is scale-free? Use Cytoscape as an example tool.
- Import PPI data into Cytoscape, and use the “network analyzer” tool

How can I find pathway and disease enrichment for these genes?  Use Toppfun as an example.
- Enter genes from PPI network into Toppfun, select pathway and disease to analyze, and set appropriate p-value

# Task E: Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes. (

What is an eQTL?  Please explain in the context of the human organism.

How do I find eQTLs associated with genes using the GTEx project?  Please provide an example using breast tissue on eQTLs that control BRCA1 expression.

# Task F: Construct an hypothesis that the genes caused the disease phenotype by mechanism X.

Design an experiment to test the hypothesis that your PPI genetic subsytem network could lead to non wild-type gene expression.

# Task G. Write a report in a github repository and send it to Feltus.

How do I create a git repository at github?  How do I add a license and make it public?

What are the basics of github markdown language?

Provide a basic overview of the github markdown language.

