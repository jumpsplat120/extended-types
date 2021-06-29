# Extended Types

Simple type monkeypatch for lua that allows customs types. Looks for the presence of a `__type` metavalue or metafunction and returns or runs and returns it respectively. If it is a metafunction, it passes the object that the type function was run on as a parameter.
