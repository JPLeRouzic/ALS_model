<h2>ALS model</h2>
(This is a work in progress which is inspired mostly by Barbeito and al. in Journal of Neural Transmission · August 2010) 
<br><br>
Amyotrophic Lateral Sclerosis (ALS) is a fatal neurodegenerative disease which is characterized by degeneration of motor neurons in the spinal cord, brain stem and motor cortex.
Despite the important efforts to find new therapies to ALS, including targeting the immune system, no efficacious drug is available today. 
This highlights the need to better understand the processes implicated.
Although the cause of the disease is currently unknown, several hypotheses including oxidative stress, protein aggregation, mitochondrial dysfunction, glutamate excitotoxicity and neuro-immune reactions are believed to participate in the motor neuron degenerative process (Boillee et al.2006a). 
While the majority of ALS cases are sporadic, 10% of them are inherited (familial), however sporadic and familial ALS produce similar pathological hallmarks, including an immune response in the affected tissues.
<img src="https://raw.githubusercontent.com/Hjertesvikt/ALS_model/master/ALS_immune_system_v3.jpeg">

In this study, we develop a mathematical model of the interactions between astrocytes and neurons during ALS disease course.
Of course, neither this model nor any other mathematical or biological model can be conclusive, only unambiguous clinical trials can provide pragmatic information. However having a model, especially a SBML model which is independant of any toolset, permits to test ideas quickly.

Mathematical modeling can be a tool to give a coherent and quantitative framework for the discussion, to suggest possible physiological mechanisms and to help plan future experiments.

<img src="https://raw.githubusercontent.com/Hjertesvikt/ALS_model/master/ALS-SBML-ScreenCapture.png">


<h2>Roadmap: </h2><br>
(inspired by Barbeito and al. Journal of Neural Transmission · August 2010) 
<br>
• Immune cells of the central nervous system, including microglia and T cells, affect the
survival of motor neurons. Based on Puri 2010, Cloutier 2009, Aubert 2005.<br>
=> Done<br>
<br>
• In a non-inflamed environment, the microglial cells remain in a state of rest or possibly "of
vigilance", presumably releasing factors having a neurotrophic influence.<br>
=> Done<br>
<br>
• Overall, the inflammatory environment and increased oxidative stress contribute to the
degeneration of motor neurons, resulting in muscle atrophy of ALS.<br>
=> Done<br>
<br>
• Activated microglial cells (pro inflammatory) and astrocytes produce toxic factors.<br>
=> Done<br>
<br>
• In a healthy human, a pre-synaptic neuron releases glutamate (Glu), binds to
glutamate receptors (GluRs) on the corresponding post-synaptic motor neuron, causing
excitation by the influx of calcium.<br>
Extracellular glutamate is rapidly removed from the synaptic cleft (Exocytosis) by
astrocytes through EAAT2 transporters.(Stobart and al. 10.3389/fncel.2013.00038)<br>
In the case of an ALS pathology, a decrease in the expression of the astrocyte glutamate
EAAT2 transporters leads to a prolonged excitation of the motoneurons and to participate in
their degeneration (excitotoxic hypothesis).<br>
=> Partly done  <br>
<br>
• Among the factors released by astrocytes, macrophage colony stimulating factor (M-CSF)
and monocyte chemoattractant protein (MCP-1) are capable of activating microglial cells
by increasing their proliferation (M-CSF) or their migration (MCP-1).<br>
=> Partly done<br>
<br>
• Microglial cells are also subject to auto-activation by releasing tumor necrosis factor-α
(TNFα) for which they express receptors 1 and 2 (TNFR 1/2) and M-CSF that act on the fms
receptor.<br>
=> Partly done<br>
<br>
• It models mitochondrial biogenesis and mitophagy, degradation processes of the lysosome
and the proteasome, and reactions of the cell to reactive oxygen species (ROS).<br>
=> Partly done<br>
<br>
• Activated (pro inflammatory) microglial cells will produce more reactive oxygen species
(ROS) such as nitric oxide (NO) via NO synthase and superoxide (O2-) by activation of
NADPH oxidases (Nox 1/2), but also pro-inflammatory cytokines 6 (IL-1β, IL-6) and
prostaglandins (PGE2) by activation of cyclooxygenase 2 (COX2).<br>
=> Partly done<br>
<br>
• Extracellular ATP, probably from damaged motor neurons, binds to microglia purinergic P2
receptors, thereby contributing to microglial activation.<br>
=> Partly done<br>
<br>
• Dendritic cells (antigen-presenting cells) secrete MCP-1, which probably participates in the
infiltration of peripheral immune cells.<br>
=> To be done<br>
<br>
• Motor neurons can also participate in glial cell activation by releasing mutant SOD1 co-
secreted with chromogranin (Cg) that can bind to CD14 acting in concert with Toll-like
receptors (TLR2 / 4).<br>
=> To be done<br>
<br>
• The adaptive immune system is also part of the degenerative response of motor neurons. T
cells (CD4+ and CD8+) from the periphery of the spinal cord enter in it during (or even
initiating) the inflammatory process of ALS.<br>
=> To be done 
(A model has been investigated: Mishra et al. Journal of Neuroinflammation (2017) 14:251)<br>
(Another interesting model is: Mishra et al. Journal of Neuroinflammation (2016) 13:212)<br>
<br>
• CD4+ lymphocytes appear to have a neuroprotective effect by directly releasing
inflammatory factors such as interleukins 4 and 10 (IL-4, IL-10) or by acting on microglial
cells to increase their neurotrophic function (production of insulin-like growth factor-1
(IGF-1)) .<br>
=> To be done<br>
<br>
• The role of infiltrating CD8+ T cells remains to determine and B cells are not present in the
spinal cord.<br>
=> To be done<br>
<br>
<br>
• Neurons become Giant Motor Units (to compensate dying neurons)<br>
(from David J on an ALS forum)<br>
=> To be done<br>
<br>
• Additionally, the two genes HtrA2 and PINK1, both of which are involved in the
mitochondrial stress response, are also integrated.<br>
=> To be done<br>
• The cell model includes the complete dopamine (DA) synthesis, metabolism, and transport
introduced by Best et al.<br>
=> To be done (adapted from Büchel et al. and merged in and then removed because it created instability)<br>
<br>





