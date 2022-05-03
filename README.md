# WeldFlux 2.0-dev
## New features
Support modeling for Additive Manufacturing.
## Usage
Enable A.M. Processing to create A.M. steps and model change interactions automatically in batch.  
PreStepName: The name of Step just ahead of the A.M. steps created.  
FirstA.M.step: The name of the First A.M.step. Letters plus numbers are recommended. e.g. 'AM1'  
CurrentPass: The element set name of current weld pass.  
PassLength: The length of current weld pass in mm.  
LayersPerInc: How many layers of elements will be activated per A.M. step.  
LayerSpace: The depth of one layer of elements.  
ElesPerLayer: How many of elements in one layer.  
BeginEleLabel: The label of any element in First activated layer.   
Select Elements by Box: Suitable for linear weld pass with uniform element size.   
Select Elements by label: Suitable for nonlinear weld pass, the label of weld pass elements should be consecutive．　　


