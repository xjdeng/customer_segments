# Creating Customer Segments

Unsupervised Learning Project (Project 3)

## Motivation

A wholesale distributor has been receiving complaints after it changed from morning deliveries every 5 days to a cheaper evening delivery 3 days a week.  Some customers were unaffected by the change while others were extremely unhappy.  We'll use unsupervised learning techniques like clustering as well as PCA and ICA to reduce the dimensionality of the data in order to investigate what's going on.

## Installation

You'll need Python 2.7 and the following libraries:

- scikit-learn
- numpy
- pandas
- ipython
- notebook
- matplotlib

Then run the following to download the respository and run it.

$ git clone https://github.com/xjdeng/customer_segments.git

$ cd customer_segments

$ ipython notebook customer_segments.git

## Template code

In this directory (`customer_segments/`), run `ipython notebook`, open `customer_segments.ipynb` and follow the instructions.

## Dataset

The dataset refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories.

It is part of a larger database published with the following paper:

Abreu, N. (2011). Analise do perfil do cliente Recheio e desenvolvimento de um sistema promocional. Mestrado em Marketing, ISCTE-IUL, Lisbon.

## Attributes

- Fresh: annual spending (m.u.) on fresh products (Continuous)
- Milk: annual spending (m.u.) on milk products (Continuous)
- Grocery: annual spending (m.u.)on grocery products (Continuous)
- Frozen: annual spending (m.u.)on frozen products (Continuous)
- Detergents_Paper: annual spending (m.u.) on detergents and paper products (Continuous)
- Delicatessen: annual spending (m.u.)on and delicatessen products (Continuous)

## Descriptive statistics

**Attribute: (Minimum, Maximum, Mean, Std. Deviation)**

- Fresh: ( 3, 112151, 12000.30, 12647.329)
- Milk: (55, 73498, 5796.27, 7380.377)
- Grocery: (3, 92780, 7951.28, 9503.163)
- Frozen: (25, 60869, 3071.93, 4854.673)
- Detergents_Paper: (3, 40827, 2881.49, 4767.854)
- Delicatessen: (3, 47943, 1524.87, 2820.106)
