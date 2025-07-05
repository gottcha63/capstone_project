# capstone_project                  +---------------------+
                  |  Static CSV Dataset  |
                  |  parking_stream.csv  |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  | Pathway Streaming   |
                  | Data Ingestion      |
                  | (replay_csv)        |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  |  Timestamp Parsing  |
                  |  Feature Engineering|
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  |  Pricing Model UDF  |
                  |  Linear Pricing     |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  | Price Calculation   |
                  | (Real-time Stream)  |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  | Visualization Layer |
                  | (Bokeh + Panel)     |
                  +----------+----------+
                             |
                             v
                  +---------------------+
                  |  Live Web App       |
                  |  Interactive Chart  |
                  +---------------------+
