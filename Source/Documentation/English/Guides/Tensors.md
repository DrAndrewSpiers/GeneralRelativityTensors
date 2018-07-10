{
 "Application" -> "Tensors",
 "Package" -> "Tensors",
 "Title" -> "Tensor package for black hole calculations",
 "Summary" ->"Tensor package providing functions for black hole calculations.",
 "Description" ->
   {"The Tensors package provides functions for computing ",
    "coordinate based for black hole calculations."},
 "Keywords" -> {"Tensors"},
 "Label" -> "Tensors Application",
 "Synonyms" -> {"Tensors"},
 "URL" -> "http://bitbucket.org/hoppese/Tensors",
 "Packages" -> {
   {"Title" -> "Tensor creation and common functions",
    "DetailedFunctions" -> {
      {"ToTensor", "Form a new Tensor"},
      {"ToMetric", "Form a new metric Tensor"},
      {"ToCurve", "Form a new Curve Tensor"},
      {"ToTensorOnCurve", "Form a new Tensor on a Curve"},
      {"RawTensorValues", "Values stored internally by Tensor"},
      {"TensorValues", "Values stored internally by Tensor, potentially evaluated on a Curve"},
      {"Rank", "Rank of Tensor"},
      {"Indices", "List of Indices of Tensor"},
      {"PossibleIndices", "List of all possible indices of Tensor"},
      {"IndexPositions","List of elements \"Up\" and \"Down\" giving the positions of Tensor indices"},
      {"Dimensions", "Dimensions is overloaded. For Tensors it gives the number of dimensions of the manifold."},
      {"Coordinates", "List of the coordinates of the Tensor"},
      {"TensorRules", "List of Rules showing Tensor values for given components"},
      {"TensorName", "Internal name of Tensor"},
      {"TensorDisplayName", "Name used for display of Tensor in notebook"},
      {"Metric", "Metric associated with the Tensor"},
      {"MetricQ", "Test whether a Tensor is a metric"},
      {"RepeatedIndexQ", "Check whether a Tensor has repeated indices"},
      {"InverseMetric", "Inverse metric associated with the Tensor"},
      {"SetTensorName", "Change the name of Tensor"}
    }
   },
   {"Title" -> "Tensor manipulation",
    "DetailedFunctions" -> {
      {"ShiftIndices", "Raise and lower indices on a Tensor"},
      {"ContractIndices", "Trace over repeated indices"},
      {"MergeTensors", "Combine an expression into a single Tensor"},
      {"MultiplyTensors", "Outer product of Tensors"},
      {"MultiplyTensorScalar", "Product of Tensor and a scalar"},
      {"SumTensors", "Sum of Tensors"}
    }
   },
   {"Title" -> "Common Tensors",
    "DetailedFunctions" -> {
      {"ChristoffelSymbol", "Connection coefficients for a metric"},
      {"RiemannTensor", "Riemann tensor for a metric"},
      {"RicciTensor", "Ricci tensor for a metric"},
      {"RicciScalar", "Ricci scalar for a metric"},
      {"EinsteinTensor", "Einstein tensor for a metric"},
      {"WeylTensor", "Weyl Tensor for a metric"},
      {"CottonTensor", "Cotton Tensor for a metric"},
      {"KretschmannScalar", "Kretschmann scalar for a metric"},
      {"MaxwellPotential", "Four vector potential for a metric"},
      {"FieldStrengthTensor","Field strength tensor for a vector potential"},
      {"MaxwellStressEnergyTensor","Stress energy tensor for a field strength tensor"}
    }
   },
   {"Title" -> "Caching Tensor values",
    "DetailedFunctions" -> {
      {"$CacheTensorValues", "Global variable for caching"},
      {"CachedTensorValues", "Values that are cached internally"},
      {"CachedTensorValues", "Remove internally cached values"}
     }
   }
 },
 "Tutorials" -> {
   "Introduction to Tensors",
   "Introduction to Tensor Curves",
   "Built in common Tensors",
   "Caching Tensor values"
 }
}