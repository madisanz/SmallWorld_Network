# SmallWorld 
Genera y analica redes tipo mundo pequeño de acuerdo con el modelo de Watts-Strogatz revisado donde la aleatorización en p = 1 es realmente igual al modelo de red de Erdős-Rényi.

En el modelo Watts-Strogatz, cada nodo vuelve a cablear sus k/2 bordes más a la derecha con probabilidad p. Esto significa que cada nodo tiene medio grado mínimo k/2. Además, en p = 1, cada borde se ha vuelto a conectar. Por tanto, la probabilidad de que exista es <k / (N-1), contrariamente al modelo ER.

En el modelo ajustado, cada par de nodos está conectado con una cierta probabilidad de conexión. Si la distancia de la red entre los nodos potencialmente conectados es d (i, j) <= k / 2, entonces están conectados con probabilidad de corto alcance p_S = k / (k + p (N-1-k)), de lo contrario, se encuentran conectados con la probabilidad de largo alcance p_L = p * p_S.p (N-1-k)), otherwise they're connected with long-range probability p_L = p * p_S.
