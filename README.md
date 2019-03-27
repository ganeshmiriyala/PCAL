# PCAL
A Matlab solver for optimization problems with orthogonality constraints.
## Problems
This solver is to solve the following problem,
> min f(X),
  s.t.  X'X=I
### Examples
+ min trace(X'AX)+trace(G'X), s.t.  X'X=I.

# References
+ Bin Gao, Xin Liu and Ya-xiang Yuan, [Parallelizable Algorithms for Optimization Problems with Orthogonality Constraints](https://arxiv.org/abs/1810.03930), SIAM Journal on Scientific Computing, accepted.

# Authors
+ [Bin Gao](https://www.gaobin.cc/) (AMSS, CAS, China)
+ [Xin Liu](http://lsec.cc.ac.cn/~liuxin/index.html) (AMSS, CAS, China)
# Copyright
Copyright (C) 2017, Bin Gao, Xin Liu

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see [http://www.gnu.org/licenses/](http://www.gnu.org/licenses/)
