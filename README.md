# Mass-Richness

Generates simulated clusters and fits the mass-richness relation assuming the CODEX seletion function.
Implements Tinker HMF (for M200mean).
Mock catalogs using the CODEX effective area dA/dTexp and selection function P(\eta^ob, M, z).
\eta computed from M, Texp and z using M-Lx relation given for M200crit. 
Cosmology should be set in "params" to be passed to Class.
Set redshift "z" and the redshift bin width "zbin_width".
