---
layout: page
title: IQMR 2025 Schedule
---

<style>
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-bg: #f8f9fa;
            --border-color: #dee2e6;
            --module-a-color: #3498db;
            --module-b-color: #2ecc71;
            --module-c-color: #f39c12;
            --module-d-color: #9b59b6;
            --unified-color: #1abc9c;
            --workshop-color: #8e44ad;
            --holiday-color: #e74c3c;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
            padding-bottom: 2rem;
        }
        
        .header {
            background-color: var(--primary-color);
            color: white;
            padding: 2rem 0;
            margin-bottom: 2rem;
            text-align: center;
        }
        
        .schedule-container {
           
        }
        
        .week-heading {
            background-color: var(--primary-color);
            color: white;
            padding: 1rem;
            text-align: center;
            font-weight: 600;
            margin-bottom: 1.5rem;
            border-radius: 4px;
        }
        
        .schedule-grid {
            width: 100%;
            border-collapse: separate;
            border-spacing: 0;
            margin-bottom: 2rem;
        }
        
        .schedule-grid th {
            background-color: var(--light-bg);
            color: var(--primary-color);
            padding: 1rem 0.5rem;
            text-align: center;
            font-weight: 600;
            border: 1px solid var(--border-color);
        }
        
        .module-header {
            text-align: center;
            vertical-align: middle;
            font-weight: 600;
            color: white;
            padding: 1rem 0.5rem;
            border: 1px solid white;
        }
        
        .special-header {
            background-color: var(--unified-color);
        }
        
        .module-a-header {
            background-color: var(--module-a-color);
        }
        
        .module-b-header {
            background-color: var(--module-b-color);
        }
        
        .module-c-header {
            background-color: var(--module-c-color);
        }
        
        .module-d-header {
            background-color: var(--module-d-color);
        }
        
        .date-header {
            width: 8%;
            font-weight: bold;
            vertical-align: middle;
            background-color: var(--primary-color);
            color: white;
            border: 1px solid white;
            text-align: center;
        }
        
        .day-name {
            font-size: 1.1rem;
            display: block;
            margin-bottom: 0.3rem;
        }
        
        .day-date {
            font-size: 0.9rem;
            display: block;
            font-weight: normal;
        }
        
        .session-cell {
            border: 1px solid var(--border-color);
            padding: 0.75rem 0.5rem;
            vertical-align: top;
            height: 160px;
            position: relative;
        }
        
        .empty-cell {
            background-color: #f8f9fa;
        }
        
        .session-content {
            height: 100%;
            overflow: hidden;
            border-radius: 4px;
            padding: 0.5rem;
            font-size: 0.85rem;
        }
        
        .special-content {
            background-color: rgba(26, 188, 156, 0.1);
            border-left: 4px solid var(--unified-color);
        }
        
        .module-a-content {
            background-color: rgba(52, 152, 219, 0.1);
            border-left: 4px solid var(--module-a-color);
        }
        
        .module-b-content {
            background-color: rgba(46, 204, 113, 0.1);
            border-left: 4px solid var(--module-b-color);
        }
        
        .module-c-content {
            background-color: rgba(243, 156, 18, 0.1);
            border-left: 4px solid var(--module-c-color);
        }
        
        .module-d-content {
            background-color: rgba(155, 89, 182, 0.1);
            border-left: 4px solid var(--module-d-color);
        }
        
        .workshop-content {
            background-color: rgba(142, 68, 173, 0.1);
            border-left: 4px solid var(--workshop-color);
        }
        
        .holiday-content {
            background-color: rgba(231, 76, 60, 0.1);
            border-left: 4px solid var(--holiday-color);
            text-align: center;
        }
        
        .session-title {
            font-weight: 600;
            margin-bottom: 0.5rem;
            line-height: 1.3;
        }
        
        .session-instructors {
            font-size: 0.8rem;
            color: #666;
            font-style: italic;
        }
        
        @media (max-width: 768px) {
            .session-cell {
                height: 140px;
                padding: 0.5rem 0.25rem;
            }
            
            .session-content {
                padding: 0.25rem;
                font-size: 0.8rem;
            }
            
            .session-title {
                font-size: 0.85rem;
                margin-bottom: 0.3rem;
            }
            
            .session-instructors {
                font-size: 0.7rem;
            }
        }
        
        .overflow-scroll {
            overflow-x: auto;
        }
</style>


    
<div class="container-fluid">
    <!-- Week 1 Schedule -->
    <div class="week-heading">Week 1: June 15-21</div>
    <div class="schedule-container overflow-scroll">
        <table class="schedule-grid">
            <thead>
                <tr>
                    <th></th>
                    <th class="module-header special-header">Special Sessions</th>
                    <th class="module-header module-a-header">Module A</th>
                    <th class="module-header module-b-header">Module B</th>
                    <th class="module-header module-c-header">Module C</th>
                    <th class="module-header module-d-header">Module D</th>
                </tr>
            </thead>
            <tbody>
                <!-- Sunday, June 15 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Sunday</span>
                        <span class="day-date">June 15</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content special-content">
                            <div class="session-title">Unified sessions</div>
                            <div class="session-instructors">Instructors: James Mahoney, Jaye Seawright and Lisa Wedeen</div>
                        </div>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                </tr>
                    
                <!-- Monday, June 16 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Monday</span>
                        <span class="day-date">June 16</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/fieldwork#preparing-for-fieldwork-and-operating-in-the-field-m1-june-16">Preparing for Fieldwork and Operating in the Field</a></div>
                            <div class="session-instructors">Instructors: Diana Kapiszewski and Lauren MacLean</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title"><a href="/modules/text-as-data#quantifying-texts-m2-june-16">Text as Data I</a></div>
                            <div class="session-instructors">Instructor: Fiona Shen-Bayh</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title"><a href="/modules/logic-of-qualitative-methods#logic-of-qualitative-methods-i-m3-june-16">Logic of Qualitative Methods I</a></div>
                            <div class="session-instructors">Instructors: James Mahoney, Gary Goertz and Laura Garcia</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Interpretive Methods I</div>
                            <div class="session-instructors">Instructors: Lisa Wedeen and William Mazzarella</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Tuesday, June 17 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Tuesday</span>
                        <span class="day-date">June 17</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content special-content">
                            <div class="session-title">Tuesday Evening Talk: Research Design</div>
                            <div class="session-instructors">James Mahoney and Baobao Zhang</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/fieldwork#research-ethics-surveys-and-interviews-m5-june-17">Research Ethics, Surveys, and Interviews</a></div>
                            <div class="session-instructors">Instructors: Lauren MacLean and Robert Mickey</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title"><a href="/modules/text-as-data#modeling-and-measuring-texts-m6-june-17">Text as Data II</a></div>
                            <div class="session-instructors">Instructor: Fiona Shen-Bayh</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title"><a href="/modules/logic-of-qualitative-methods#logic-of-qualitative-methods-ii-m7-june-17">Logic of Qualitative Methods II</a></div>
                            <div class="session-instructors">Instructors: James Mahoney, Gary Goertz and Laura Garcia</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Interpretive Methods II</div>
                            <div class="session-instructors">Instructors: Lisa Wedeen and William Mazzarella</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Wednesday, June 18 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Wednesday</span>
                        <span class="day-date">June 18</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/fieldwork#interviews-focus-groups-and-observation-m9-june-18">Interviews, Focus Groups, and Observation</a></div>
                            <div class="session-instructors">Instructors: Diana Kapiszewski and Lauren MacLean</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Qualitative Causal Inference</div>
                            <div class="session-instructors">Instructors: David Waldner and Ezequiel Gonzalez-Ocantos</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Comparative Historical Analysis I</div>
                            <div class="session-instructors">Instructor: Marcus Kreuzer</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Interpretation and History I</div>
                            <div class="session-instructors">Instructor: Amel Ahmed</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Thursday, June 19 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Thursday</span>
                        <span class="day-date">June 19</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content special-content">
                            <div class="session-title">Film Screening and Discussion: Raise the Roof</div>
                            <div class="session-instructors">Jamila Michener and Gretchen Purser</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content holiday-content">
                            <div class="session-title">Juneteenth Holiday</div>
                            <div class="session-instructors">No Module Sessions</div>
                        </div>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                </tr>
                    
                <!-- Friday, June 20 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Friday</span>
                        <span class="day-date">June 20</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/fieldwork#archival-research-and-dynamic-research-design-m13-june-20">Archival Research and Dynamic Research Design</a></div>
                            <div class="session-instructors">Instructors: Diana Kapiszewski, Lauren MacLean, and Robert Mickey</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Qualitative Causal Inference</div>
                            <div class="session-instructors">Instructors: David Waldner and Ezequiel Gonzalez-Ocantos</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Comparative Historical Analysis II</div>
                            <div class="session-instructors">Instructor: Marcus Kreuzer</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Interpretation and History II</div>
                            <div class="session-instructors">Instructor: Amel Ahmed</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Saturday, June 21 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Saturday</span>
                        <span class="day-date">June 21</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content workshop-content">
                            <div class="session-title">Weekend Workshops – Advances in Qualitative and Multi-Method Research</div>
                        </div>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                </tr>
            </tbody>
        </table>
    </div>
        
    <!-- Week 2 Schedule -->
    <div class="week-heading">Week 2: June 22-27</div>
    <div class="schedule-container overflow-scroll">
        <table class="schedule-grid">
            <thead>
                <tr>
                    <th></th>
                    <th class="module-header special-header">Special Sessions</th>
                    <th class="module-header module-a-header">Module A</th>
                    <th class="module-header module-b-header">Module B</th>
                    <th class="module-header module-c-header">Module C</th>
                    <th class="module-header module-d-header">Module D</th>
                </tr>
            </thead>
            <tbody>
                <!-- Sunday, June 22 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Sunday</span>
                        <span class="day-date">June 22</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content workshop-content">
                            <div class="session-title">Weekend Workshops – Emerging Methodologists Workshop</div>
                        </div>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell empty-cell"></td>
                </tr>
                    
                <!-- Monday, June 23 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Monday</span>
                        <span class="day-date">June 23</span>
                    </td>
                    <td class="session-cell">
                        <div class="session-content special-content">
                           <div class="session-title">Lunch Talk: Emerging Methodologists</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/integrating-qualitative-and-experimental-methods#integrating-qualitative-and-experimental-methods-i-m17-june-23">Integrating Qualitative and Experimental Methods I</a></div>
                            <div class="session-instructors">Instructors: Christopher Carter, Charles Crabtree, Tesalia Rizzo, Guadelupe Tuñón</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Causal Inference from Causal Models I</div>
                            <div class="session-instructors">Instructor: Alan Jacobs</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Choosing Spatial Units of Analysis</div>
                            <div class="session-instructors">Instructor: Hillel Soifer</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Ethnographic Methods I</div>
                            <div class="session-instructors">Instructors: Sarah Parkinson and Kanisha Bond</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Tuesday, June 24 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Tuesday</span>
                        <span class="day-date">June 24</span>
                    </td>
                    <td class="session-cell empty-cell">
                        <div class="session-content special-content">
                            <div class="session-title">Tuesday Evening Talk: Writing Qualitative Research</div>
                            <div class="session-instructors">Alan Jacobs</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/integrating-qualitative-and-experimental-methods#integrating-qualitative-and-experimental-methods-ii-m21-june-24">Integrating Qualitative and Experimental Methods II</a></div>
                            <div class="session-instructors">Instructors: Christopher Carter, Charles Crabtree, Tesalia Rizzo, Guadelupe Tuñón</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Causal Inference from Causal Models II</div>
                            <div class="session-instructors">Instructor: Alan Jacobs</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Bayesian Inference for Qualitative Research II</div>
                            <div class="session-instructors">Instructor: Tasha Fairfield</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Ethnographic Methods II</div>
                            <div class="session-instructors">Instructors: Sarah Parkinson and Kanisha Bond</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Wednesday, June 25 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Wednesday</span>
                        <span class="day-date">June 25</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title"><a href="/modules/integrating-qualitative-and-experimental-methods#integrating-qualitative-and-experimental-methods-iii-m25-june-25">Integrating Qualitative and Experimental Methods III</a></div>
                            <div class="session-instructors">Instructors: Christopher Carter, Charles Crabtree, Tesalia Rizzo, Guadelupe Tuñón</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Causal Inference from Causal Models III</div>
                            <div class="session-instructors">Instructor: Alan Jacobs</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Bayesian Inference for Qualitative Research III</div>
                            <div class="session-instructors">Instructor: Tasha Fairfield</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title">Ethnographic Methods III</div>
                            <div class="session-instructors">Instructors: Sarah Parkinson and Kanisha Bond</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Thursday, June 26 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Thursday</span>
                        <span class="day-date">June 26</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title">Geographic Information Systems I</div>
                            <div class="session-instructors">Instructor: Jonnell Robinson</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Multi-Method Research I</div>
                            <div class="session-instructors">Instructor: Jaye Seawright</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Process Tracing and Typological Theories I</div>
                            <div class="session-instructors">Instructor: Andrew Bennett</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title"><a href="/modules/rethinking-small-n#re-thinking-small-n-comparisons-i-m32-june-26">Re-thinking Small-N Comparisons I</a></div>
                            <div class="session-instructors">Instructor: Nicholas Rush</div>
                        </div>
                    </td>
                </tr>
                    
                <!-- Friday, June 27 -->
                <tr>
                    <td class="date-header">
                        <span class="day-name">Friday</span>
                        <span class="day-date">June 27</span>
                    </td>
                    <td class="session-cell empty-cell"></td>
                    <td class="session-cell">
                        <div class="session-content module-a-content">
                            <div class="session-title">Geographic Information Systems II</div>
                            <div class="session-instructors">Instructor: Jonnell Robinson</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-b-content">
                            <div class="session-title">Multi-Method Research II</div>
                            <div class="session-instructors">Instructor: Jaye Seawright</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-c-content">
                            <div class="session-title">Process Tracing and Typological Theories II</div>
                            <div class="session-instructors">Instructor: Andrew Bennett</div>
                        </div>
                    </td>
                    <td class="session-cell">
                        <div class="session-content module-d-content">
                            <div class="session-title"><a href="/modules/rethinking-small-n#re-thinking-small-n-comparisons-ii-m36-june-27">Re-thinking Small-N Comparisons II</a></div>
                            <div class="session-instructors">Instructor: Nicholas Rush Smith</div>
                        </div>
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</div>

