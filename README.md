# Marvel-and-DC-Character-WIkilink-Graph

- We downloaded all the Marvel and DC charecter wikitext from wikimedia at [Data Marvel Directory](./data/Marvel) and [Data DC Directory](./data/DC). We also created a pickle file of Panda Dataframe containing all the text of character in [`data`](./data) directory named `Marvel_Characters_Wikitext.pkl` & `DC_Characters_Wikitext.pkl` 
- We created a directed graph (DiGraph) containing all the charecter as a node and link between their Wikipages as Edge. Saved this graph as a pickle file in [data](./data/) directory named `comic_characters_universe.gpickle`. Also in each node their Universe and length is saved as data.

Code for all the above tasks is in  `Marvel and DC Character WIkilink Graph.ipynb` file.
