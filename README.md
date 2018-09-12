# ALS_model
(This is a work in progress)

Amyotrophic Lateral Sclerosis (ALS) is a fatal neurodegenerative disease which is characterized by degeneration of motor neurons in the spinal cord, brain stem and motor cortex.
Despite the important efforts to find new therapies to ALS, including targeting the immune system, no efficacious drug is available today. 
This highlights the need to better understand the processes implicated.
Although the cause of the disease is currently unknown, several hypotheses including oxidative stress, protein aggregation, mitochondrial dysfunction, glutamate excitotoxicity and neuro-immune reactions are believed to participate in the motor neuron degenerative process (Boillee et al.2006a). 
While the majority of ALS cases are sporadic, 10% of them are inherited (familial), however sporadic and familial ALS produce similar pathological hallmarks, including an immune response in the affected tissues.
![Alt text](https://raw.githubusercontent.com/Hjertesvikt/ALS_model/master/ALS_immune_system_v2.jpeg)

In this study, we develop a mathematical model of the interactions between astrocytes and neurons during ALS disease course.
Of course, neither this model nor any other mathematical or biological model can be conclusive, only unambiguous clinical trials can provide pragmatic information. However having a model, especially a SBML model which is independant of any toolset, permits to test ideas quickly.

Mathematical modeling can be a tool to give a coherent and quantitative framework for the discussion, to suggest possible physiological mechanisms and to help plan future experiments.

#Roadmap:
• Immune cells of the central nervous system, including microglia and T cells, affect the
survival of motor neurons.
=> Done

• In a healthy human, a pre-synaptic neuron releases glutamate (Glu), which binds to
glutamate receptors (GluRs) on the corresponding post-synaptic motor neuron, causing
excitation by the influx of calcium.
=> To be done

• Extracellular glutamate is rapidly removed from the synaptic cleft (Exocytosis) by
astrocytes through EAAT2 transporters.
=> To be done

• In a non-inflamed environment, the microglial cells remain in a state of rest or possibly "of
vigilance", presumably releasing factors having a neurotrophic influence.
=> Done

• In the case of an ALS pathology, a decrease in the expression of the astrocyte glutamate
EAAT2 transporters leads to a prolonged excitation of the motoneurons and to participate in
their degeneration (excitotoxic hypothesis).
=> To be done

• Activated microglial cells (pro inflammatory) and astrocytes produce toxic factors.
=> Partly done

• Among the factors released by astrocytes, macrophage colony stimulating factor (M-CSF)
and monocyte chemoattractant protein (MCP-1) are capable of activating microglial cells
by increasing their proliferation (M-CSF) or their migration (MCP-1).
=> To be done

• Microglial cells are also subject to auto-activation by releasing tumor necrosis factor-α
(TNFα) for which they express receptors 1 and 2 (TNFR 1/2) and M-CSF that act on the fms
receptor.
=> To be done

• Activated (pro inflammatory) microglial cells will produce more reactive oxygen species
(ROS) such as nitric oxide (NO) via NO synthase and superoxide (O2-) by activation of
NADPH oxidases (Nox 1/2), but also pro-inflammatory cytokines 6 (IL-1β, IL-6) and
prostaglandins (PGE2) by activation of cyclooxygenase 2 (COX2).
=> To be done

• Extracellular ATP, probably from damaged motor neurons, binds to microglia purinergic P2
receptors, thereby contributing to microglial activation.
=> To be done

• Motor neurons can also participate in glial cell activation by releasing mutant SOD1 co-
secreted with chromogranin (Cg) that can bind to CD14 acting in concert with Toll-like
receptors (TLR2 / 4).
=> To be done

• The adaptive immune system is also part of the degenerative response of motor neurons. T
cells (CD4+ and CD8+) from the periphery of the spinal cord enter in it during (or even
initiating) the inflammatory process of ALS.
=> To be done (but some progress had been made)

• CD4+ lymphocytes appear to have a neuroprotective effect by directly releasing
inflammatory factors such as interleukins 4 and 10 (IL-4, IL-10) or by acting on microglial
cells to increase their neurotrophic function (production of insulin-like growth factor-1
(IGF-1)) .
=> To be done

• The role of infiltrating CD8+ T cells remains to determine and B cells are not present in the
spinal cord.
=> To be done

• Dendritic cells (antigen-presenting cells) secrete MCP-1, which probably participates in the
infiltration of peripheral immune cells.
=> To be done

• Overall, the inflammatory environment and increased oxidative stress contribute to the
degeneration of motor neurons, resulting in muscle atrophy of ALS.
=> Done

• Neurons become Giant Motor Units (to compensate dying neurons)
=> To be done

• The cell model includes the complete dopamine (DA) synthesis, metabolism, and transport
introduced by Best et al.
=> To be done (merged in and removed because it created instability)

• It models mitochondrial biogenesis and mitophagy, degradation processes of the lysosome
and the proteasome, and reactions of the cell to reactive oxygen species (ROS).
=> To be done (A model was studied but not merged because fear of insstability)

• Additionally, the two genes HtrA2 and PINK1, both of which are involved in the
mitochondrial stress response, are also integrated.
=> To be done





