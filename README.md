# dssp-3.0.0
DSSP for Mac OS Mojave with boost-1.67

The source code was modified as follows:
- Correct all the boost/tr1/tuple with boost/tuple/tuple;
- Repleace the tr1::tuple with boost::tuple;
- Remove -static from makefile
- Uncomment "BOOST_LIB_SUFFIX = -mt" from make.config;


then make the mkdssp
