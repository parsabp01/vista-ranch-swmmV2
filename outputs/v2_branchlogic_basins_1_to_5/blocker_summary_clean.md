# Blocker Summary (Clean)

1. TRUE missing source nodes: 40
2. source lookup / normalization bugs: 12
3. true missing required junction fields (AC missing): 65
4. direction parsing failures: 0
5. remaining graph errors: pending manual exception cleanup
2. source lookup / normalization bugs: 0
3. true missing required junction fields: 153
4. direction parsing failures: 0
5. remaining graph errors: 0
1. TRUE missing source nodes: 34
2. source lookup / normalization bugs: 6
3. true missing required junction fields: 153
4. direction parsing failures: 0
5. remaining graph errors: 236

## Top remaining blockers
- row 7: J_71_9 -> J_72 / missing_junction_source
- row 8: IN_77_6 -> J_71_8 / missing_inlet_source
- row 9: J_71_6 -> J_71_7 / missing_junction_source
- row 9: J_71_4 -> J_71_7 / missing_junction_source
- row 10: IN_77_5 -> J_71_6 / missing_junction_source
- row 10: J_71_5 -> J_71_6 / missing_junction_source
- row 11: IN_77_4 -> J_71_5 / missing_inlet_source
- row 12: J_71_2 -> J_71_4 / missing_junction_source|missing_required_junction_fields:AC
- row 12: J_71_3 -> J_71_4 / missing_junction_source|missing_required_junction_fields:AC
- row 13: IN_77_2 -> J_71_3 / missing_required_junction_fields:AC
- row 14: IN_77 -> J_71_2 / missing_required_junction_fields:AC
- row 14: IN_77_1 -> J_71_2 / missing_inlet_source|missing_required_junction_fields:AC
- row 15: J_71_1 -> J_71_9 / missing_junction_source|missing_junction_source
- row 16: J_71 -> J_71_1 / missing_junction_source
- row 16: IN_76_5 -> J_71_1 / missing_junction_source
- row 17: J_70_4 -> J_71 / missing_junction_source
- row 18: IN_76_43 -> J_70_4 / missing_inlet_source|missing_junction_source
- row 18: J_70_3 -> J_70_4 / missing_junction_source
- row 20: J_70_1 -> J_70_2 / missing_junction_source
- row 21: IN_76_3 -> J_70_1 / missing_junction_source
- row 22: IN_76_1 -> J_70 / missing_inlet_source
- row 23: J_68_1 -> J_69 / missing_junction_source
- row 23: J_68_05 -> J_69 / missing_required_junction_fields:AC
- row 23: J_65_3 -> J_69 / missing_required_junction_fields:AC
- row 24: J_68 -> J_68_05 / missing_required_junction_fields:AC|missing_required_junction_fields:AC
- row 25: IN_75_3 -> J_68 / missing_required_junction_fields:AC
- row 25: IN_75_4 -> J_68 / missing_inlet_source|missing_required_junction_fields:AC
- row 26: IN_75_5 -> J_68_1 / missing_junction_source
- row 26: IN_75_6 -> J_68_1 / missing_inlet_source|missing_junction_source
- row 27: J_65_1 -> J_65_3 / missing_junction_source|missing_required_junction_fields:AC
- row 27: J_65_25 -> J_65_3 / missing_required_junction_fields:AC|missing_required_junction_fields:AC
- row 28: IN_75_25 -> J_65_25 / missing_required_junction_fields:AC
- row 28: J_65_2 -> J_65_25 / missing_required_junction_fields:AC|missing_required_junction_fields:AC
- row 29: IN_75_2 -> J_65_2 / missing_required_junction_fields:AC
- row 29: IN_75_1 -> J_65_2 / missing_inlet_source|missing_required_junction_fields:AC
- row 30: J_65 -> J_65_1 / missing_junction_source
- row 30: IN_75 -> J_65_1 / missing_junction_source
- row 30: IN_74 -> J_65_1 / missing_junction_source
- row 35: J_55 -> J_57 / missing_required_junction_fields:AC
- row 36: IN_56 -> J_55 / missing_required_junction_fields:AC
- row 36: IN_56_1 -> J_55 / missing_required_junction_fields:AC
- row 54: J_36 -> J_37 / missing_required_junction_fields:AC
- row 55: IN_39 -> J_36 / missing_required_junction_fields:AC
- row 89: J_4_1 -> J_5 / missing_junction_source
- row 90: IN_6 -> J_4_1 / missing_junction_source
- row 90: IN_6_1 -> J_4_1 / missing_junction_source
- row 90: IN_7 -> J_4_1 / missing_junction_source
- row 95: J_134 -> O_134 / missing_required_junction_fields:AC
- row 96: IN_162 -> J_134 / missing_required_junction_fields:AC
- row 96: J_133 -> J_134 / missing_required_junction_fields:AC
