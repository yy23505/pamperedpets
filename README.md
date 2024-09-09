# pamperedpets
{
    "name": "Attack Tree",
    "nodes": [
        {
            "id": "node1",
            "type": "AND", // OR, AND, or LEAF
            "children": ["node2", "node3"],
            "value": null // monetary amount or probability
        },
        {
            "id": "node2",
            "type": "LEAF",
            "children": [],
            "value": 100.0 // monetary amount
        },
        {
            "id": "node3",
            "type": "LEAF",
            "children": [],
            "value": 0.5 // probability
        },
        ...
    ]
}
