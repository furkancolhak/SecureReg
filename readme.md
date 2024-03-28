We gathered data from two different sources to create our dataset. Initially, we obtained benign (safe) website URLs from the Alexa 1m \cite{Alexa} dataset by randomly selecting them. Then, we gathered malicious URLs from OpenPhish. Using a WHOIS tool designed explicitly for open-source intelligence (OSINT), we extracted domain names from these URLs and removed their top-level domains (TLDs). Subsequently, we eliminated duplicate domain names and those already present in the top 100k list on Alexa. This step was crucial as we utilized the Alexa top 100k \cite{Alexa} list as a fictional database of registrants. 

Table \ref{tab:data} shows data distribution in the SecReg Dataset.

\begin{table}[H]
  \centering
  \caption{Data Distribution in SecReg Dataset}
  \label{tab:data}
  \begin{tabular}{lccc}
    \toprule
    & \textbf{Benign} & \textbf{Malicious} & \textbf{Total} \\
    \midrule
    \textbf{SecReg Dataset} & 4,198 & 4,702 & 8,900 \\
    \bottomrule
  \end{tabular}
\end{table}
