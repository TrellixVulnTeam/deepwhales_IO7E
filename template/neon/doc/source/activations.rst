.. ---------------------------------------------------------------------------
.. Copyright 2015 Nervana Systems Inc.
.. Licensed under the Apache License, Version 2.0 (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at
..
..      http://www.apache.org/licenses/LICENSE-2.0
..
.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.
.. ---------------------------------------------------------------------------

Activations
===========
These classes apply a transformation to the outputs from each node in a
layer.  These transformations are often non-linear in nature.

Identity
--------
.. autosummary::
   neon.transforms.activation.Identity

Rectified Linear
----------------
.. autosummary::
   neon.transforms.activation.Rectlin

Softmax
-------
.. autosummary::
   neon.transforms.activation.Softmax

Tanh
----
.. autosummary::
   neon.transforms.activation.Tanh

Logistic
--------
.. autosummary::
   neon.transforms.activation.Logistic
